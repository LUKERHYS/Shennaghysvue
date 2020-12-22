<template>
  <div class="home-container">
    <div class="home">
      Home
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  // data: function() {
  //   return {
  //     postData: {
  //       title: "This is a facebook post",
  //       image: "./assets/swirl_pattern.png",
  //       content: "This is the post info"
  //     }
  //   }
  // },
  components: {
  },
};
</script>
<style>
.home-container {
  position: absolute;
  display: inline-flex;
  justify-content: center;
  align-items: center;
}
.home {
  width: 75vw;
  height: auto;
  padding:2em;
  background-color: #F2F1E8;
}
</style>
