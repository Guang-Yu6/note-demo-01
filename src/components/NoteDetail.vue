<template>
  <div>
    <h1>{{msg}}:{{$route.params.noteId}}</h1>
  </div>
</template>

<script>
export default {
  name: "NoteDetail",
  data(){
    return {
      msg:'笔记本详情页a'
    }
  }
}
</script>

<style scoped>
h1 {
  color:bisque;
}
</style>
