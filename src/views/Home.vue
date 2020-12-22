<template>
  <div>
      <h1>News</h1>
      <grid-container :posts="posts"/>
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
</style>
