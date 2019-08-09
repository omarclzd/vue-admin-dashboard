<template>
  <div class="container">
    <div class="login"></div>
  </div>
</template>

<script>
export default {
  name: "SignIn"
};
</script>

<style lang="scss" scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;

  min-height: 100vh;
}

.login {
  height: 50px;
  width: 50px;
  background: red;
}
</style>