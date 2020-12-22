<template>
    <div class="grid-card">
        <h2>{{this.post.title}}</h2>
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
    text-align: left;
    padding: 0 2%;
}
p {
  font-family: Helvetica, Arial, sans-serif;
}
</style>
