<template>
  <div class="home-container">
    <div class="home">
      Home
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
        post1: { title: 'Title 1', content: 'Content text 1', Img: 'URLS' },
        post2: { title: 'Title 2', content: 'Content text 2', Img: 'URLS' },
        post3: { title: 'Title 3', content: 'Content text 3', Img: 'URLS' },
        post4: { title: 'Title 4', content: 'Content text 4', Img: 'URLS' },
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
}
.home {
  width: 75vw;
  height: auto;
  padding:2em;
  background-color: #F2F1E8;
}
</style>
