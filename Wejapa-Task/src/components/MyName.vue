<template>
<div class="name">
  <h1>{{name}}</h1>
</div>
</template>
<script>
export default {
  name: 'MyName',
  props: {
    name: String
  }  
}
</script>
<style>
h1{
  text-align: center;
  font-size: 60px;
  font-weight: 900;
}
</style>

