<template>
  <div>
    Hello world {{message}}
    <p v-text="message"></p>
  </div>
</template>

<script>
export default {
  name: "helloWorld",
  data: function() {
    return {
      message: "Vue is awesome"
    };
  }
};
</script>

<style>
</style>

