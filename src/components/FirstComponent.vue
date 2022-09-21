<template>
  <h1>welcome <b>{{username}}</b> to my first component ! </h1>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<script>
export default {
  name: "FirstComponent",
  props: {
    username: String
  },
  data() {
    return {
      count : 0
    }
  }
}
</script>

<style scoped>
button {
  font-weight: bold;
}
</style>