<script>
export default {
  name: 'App',
  data() {
    return {
      saluto: 'Hello world!'
    }
  },
  methods: {

  }
}
</script>

<template>
 <h1> {{  saluto  }}</h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

h1{
  color: rgb(143, 143, 0)
}
</style>
