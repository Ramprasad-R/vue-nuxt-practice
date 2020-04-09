<template>
  <div>
    <h1>About Me</h1>
    <p>This is About me page</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About me",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "About me"
        }
      ]
    };
  }
};
</script>

<style>
</style>