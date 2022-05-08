<template>
  <div>
    <h1>
      {{msg}}
    </h1>
  </div>
</template>

<script>
export default {
  name: "TrashDetail",
  data(){
    return {
      msg:'回收站笔记详情页'
    }
  }
}
</script>

<style scoped>
h1 {
  color:seagreen;
}
</style>
