<template>
  <div>
    <div>
      <input type="text" />
      <button>추가하기</button>
    </div>
    <ul>
      <ListItemVue />
    </ul>
  </div>
</template>
<script>
import ListItemVue from "./ListItem.vue";
export default {
  component: {
    ListItemVue,
  },
};
</script>
<style lang=""></style>
