<script setup>
import { ref } from 'vue'

const studentName = ref('')
const studentId = ref('')
const course = ref('')
const yearLevel = ref('')
const email = ref('')

const emit = defineEmits(['student-submitted'])

function submitForm() {
  const student = {
    name: studentName.value,
    id: studentId.value,
    course: course.value,
    yearLevel: yearLevel.value,
    email: email.value
  }

  emit('student-submitted', student)
}
</script>

<template>
  <form @submit.prevent="submitForm">
        <h1>Student information form</h1>
        <input v-model= "fname" type ="text" placeholder="Enter your name">
    <br><br>

<input v-model= "name" type ="text" placeholder="Enter your name">
    <br><br>

    <label>Course:</label>
    <select v-model="course" required>
      <option value="">Select Course</option>
      <option value="BSIT">BSIT</option>
      <option value="BSCS">BSCS</option>
      <option value="BSIS">BSIS</option>
    </select>
    <br><br>

    <label>Year Level:</label><br>

    <input v-model="yearLevel" type="radio" value="1st Year" required>
    1st Year
    <input v-model="yearLevel" type="radio" value="2nd Year">
    2nd Year
    <input v-model="yearLevel" type="radio" value="3rd Year">
    3rd Year
    <input v-model="yearLevel" type="radio" value="4th Year">
    4th Year
    <br><br>

    <label>Email:</label><br>
    <input v-model="email" type="email" required>
    <br><br>

    <button type="submit">Submit Student</button>


  </form>
</template>