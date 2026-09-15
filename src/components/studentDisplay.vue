<script setup>
defineProps({
  student: Object
})
</script>

<template>
  <div v-if="student">
    <h2>Student Information</h2>
    
    <p>Name: {{ studentName }}</p>
    <p>Student ID: {{ studentId }}</p>
    <p>Course: {{course }}</p>
    <p>Year Level: {{ yearLevel }}</p>
    <p>Email: {{ email }}</p>
  </div>
</template>