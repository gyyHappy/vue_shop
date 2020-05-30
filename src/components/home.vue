<template>
    <div>
      <el-button type="info" round @click="logout">推出</el-button>
    </div>
</template>

<script>
    export default {
      methods: {
        logout () {
          window.sessionStorage.clear();
          this.$router.push("/login");
        }
      }
    }
</script>

<style scoped>

</style>
