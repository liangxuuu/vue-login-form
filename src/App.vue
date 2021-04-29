<template>  
  <div id="app">
    <login-form/>
  </div>
</template>

<script>
import LoginForm from "./components/LoginForm";

export default {
  name: "App",
  components: {
    LoginForm
  },
  method: {
    function() {
      hash.replace(/(:|\.|\[|\]|,|=)/g, "\\$1");
    }
  }
};
</script>

<style>

</style>
