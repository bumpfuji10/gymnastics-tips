<template>
  <!-- <UsersIndex /> -->
  <div>
    <h1 class="text-2xl italic font-mono">Gymnastics Tipsへようこそ！</h1>
    <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">ボタン</button>
  </div>
</template>

<script>
import UsersIndex from './UsersIndex.vue';

export default {
  name: 'HomeView',
  components: {
    UsersIndex
  }
}
</script>
