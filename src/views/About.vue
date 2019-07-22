<template>
  <div class="about">
    <h1>This is an about page</h1>
    {{msg1}}
  </div>
</template>

<script>
  import store from '@/store'

  export default {
    name: 'about',
    store,
    data(){
      return {
        msg1: store.state.count
      }
    }
  };
</script>
