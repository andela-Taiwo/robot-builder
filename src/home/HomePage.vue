<template>
  <div class="home">
  <div>
    <img src="../assets/robot-home.png" class="robot" aria-hidden="true">
  </div>
  <div>
    <a href=""> Getting Started </a> Build your own robot
  </div>

  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .robot {
    height: 300px;
  }
  .home {
    text-align: center;
  }

</style>
