<template>
  <div>
    <div class="hello_title">{{ msg }}</div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: null,
    };
  },
  mounted() {
    let that = this;
    setTimeout(function(){
      that.msg = "Welcome to Your Chili App"
    }, 1000 )
  }
};
</script>

<style scoped>
.hello_title {
  font-size: 0.32rem;
  margin: 20%;
}
</style>
