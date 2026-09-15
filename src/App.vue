<script setup>
import { ref } from 'vue'
import formactivity from './components/formactivity.vue'
import Formactivity from './components/formactivity.vue';
// import studentDisplay from './components/studentDisplay.vue'


</script>

<template>
  <div>
    <formactivity />
    <!-- <studentForm /> -->
  </div>
</template>


<!-- <template>
  <div>
    <p>{{ message }}</p>

    <button @click="changeMessage('Hi world!')">
      Change Message
    </button>

    <button @click="clear">
      Clear
    </button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'hello world!'
    }
  },

  methods: {
    changeMessage(newMessage) {
      this.message = newMessage
    },

    clear() {
      this.message = ''
    }
  }
}
</script> -->
