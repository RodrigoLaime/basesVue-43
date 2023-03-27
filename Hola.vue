<template>
  <div>
    <p>Hola Mundo</p>
    <div>{{ text }}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: 'hola'
    }
  }
};
</script>

<style>
p {
  color: red;
}
</style>