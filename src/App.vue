<template>
  <div class="name">{{ name }}</div>
</template>

<script>
export default {
  setup() {
    const name = 'Kossie Coder^^';

    return {
      name
    };
  },
}
</script>

<style scoped>
.name {
  color: red;
}
</style>