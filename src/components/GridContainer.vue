<template>
    <div class="grid-container">
        <grid-card v-for="(post, index) in this.posts" :key="index" :post="post"/>
    </div>
</template>

<script>
import GridCard from './GridCard.vue';

export default {
  name: 'grid-container',
  props: ['posts'],
  components: {
    'grid-card': GridCard,
  },
};
</script>

<style lang="css" scoped>
.grid-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

</style>
