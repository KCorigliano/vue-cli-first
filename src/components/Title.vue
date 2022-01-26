<template>
  <div class="title">
    <h1>My first App with Vue CLI!</h1>
  </div>
</template>

<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>
<style>
.title{
    color: red;
}
</style>
