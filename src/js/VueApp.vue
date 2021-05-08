<template>
  <p>{{ message }}</p>
</template>

<script>
// import { defineComponent } from '@vue/composition-api'
export default {
  data: () => {
    console.log('Vue test')
    return {
      message: 'Hey, this is vue!'
    }
  }
}
</script>

<style scoped>
p {
  color: green;
}
</style>