<template>
  <div class="grapes">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Grapes and Strawberries',
      message: 'I like grapes and strawberries'
    }
  }
};
</script>

<style>
.grapes {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: #6a329f;
  }
</style>