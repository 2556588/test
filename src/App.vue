<template>
  <div>
    <my-add></my-add>
    <my-del></my-del>
  </div>
</template>
<script>
import add from './components/add.vue'
import del from './components/del.vue'
export default {
  data() {
    return {}
  },
  components: {
    'my-add': add,
    'my-del': del
  }
}
</script>
<style lang="less" scoped></style>
