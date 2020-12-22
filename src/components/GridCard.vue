<template>
    <div class="grid-card">
        <H1>{{this.post.title}}</H1>
        <p>{{this.post.content}}</p>
    </div>
</template>

<script>
export default {
  name: 'grid-card',
  props: ['post'],
};
</script>

<style lang="css" scoped>
.grid-card {
    background-color: hotpink;
    width: 20%;
    height: 20%;
    margin: 2px;
}
</style>
