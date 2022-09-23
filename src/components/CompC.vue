<template>
  <h1>Component C</h1>
  <h2>user Name by Provide_inject:{{ userName }}</h2>
  <button @click="someFuc">click me</button>
</template>

<script>
export default {
  inject: ["userName", "someFuc"],
};
</script>

<style></style>
