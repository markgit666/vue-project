<template>
  <div>info页面
    <button type="button" @click="add()">添加</button>
  </div>
</template>

<script>
  import store from '@/store';

  export default {
    name: 'info',
    store,
    methods: {
      add() {
        store.commit("increase")
      }
    }
  };
</script>

<style scoped>

</style>
