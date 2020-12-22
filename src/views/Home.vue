<template>
  <div class="home-container">
    <div class="home">
      <h1>News</h1>
      <grid-container :posts="posts"/>
    </div>
  </div>
</template>

<script>
import GridContainer from '../components/GridContainer.vue';

export default {
  name: 'Home',
  data() {
    return {
      posts: {
        post1: { title: 'Shen 2021', content: 'As I am sure you are all desparate to know, will Shen happen in 2021? The honest answer is we cant be sure but we are aiming for a local festival due to the amount of travel restrictions on and off the island. More grat things to come, wacth this space.', Img: 'URLS' },
        post2: { title: 'Shen 2021', content: 'As I am sure you are all desparate to know, will Shen happen in 2021? The honest answer is we cant be sure but we are aiming for a local festival due to the amount of travel restrictions on and off the island. More grat things to come, wacth this space.', Img: 'URLS' },
        post3: { title: 'Shen 2021', content: 'As I am sure you are all desparate to know, will Shen happen in 2021? The honest answer is we cant be sure but we are aiming for a local festival due to the amount of travel restrictions on and off the island. More grat things to come, wacth this space.', Img: 'URLS' },
        post4: { title: 'Shen 2021', content: 'As I am sure you are all desparate to know, will Shen happen in 2021? The honest answer is we cant be sure but we are aiming for a local festival due to the amount of travel restrictions on and off the island. More grat things to come, wacth this space.', Img: 'URLS' },
      },
    };
  },
  components: {
    'grid-container': GridContainer,
  },
};
</script>
<style>
.home-container {
  position: absolute;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  -webkit-box-shadow: 0px 0px 14px 0px rgba(0,0,0,0.39);
  -moz-box-shadow: 0px 0px 14px 0px rgba(0,0,0,0.39);
  box-shadow: 0px 0px 14px 0px rgba(0,0,0,0.39);
}
.home {
  width: 75vw;
  height: auto;
  padding:2em;
  background-color: #F2F1E8;
}
h1 {
  size: 200px;
}
</style>
