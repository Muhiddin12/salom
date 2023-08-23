<template>
  <div class="home">
    <h2>This is a home page</h2>
    <Test />
  </div>
</template>

<script>
import Test from "../components/Test.vue";

export default {
  name: "HomeView",
  components: {
    Test,
  },
};
</script>

<style scoped>
.home {
  width: 100%;
  background: #ddb7b7;
  min-height: 300px;
}
</style>
