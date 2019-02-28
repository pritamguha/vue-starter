<template>
  <header>
    <h1>{{title}}</h1>
  </header>
</template>

<script>
import { mapState } from "vuex";
export default {
  name: "Header",
  computed: {
      ...mapState([
          'title'
      ])
  }
};
</script>

<style scoped>
</style>


