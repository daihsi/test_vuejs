<template>
  <p>いいね({{ number }})</p>
  <button @click="increment">+1</button>
</template>

<script>
  export default {
    data() {
      return {
        number: 10,
      };
    },
    methods: {
      increment() {
        this.number += 1;
      }
    }
  }
</script>

<style spcoped>
  p {
    border: 1px solid red;
  }
</style>
