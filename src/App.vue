<template>
  <div>
    <div class="post">
      <div><strong>Название:</strong>Пост о JavaScript</div>
      <div><strong>Описание:</strong>JavaScript универсальный язык програмирования</div>
    </div>
  </div>

</template>

<script>
export default {
  data() {
    return {
      posts: [
        {id: 1, title: 'Javascript1', body: 'Описание поста1'},
        {id: 2, title: 'Javascript2', body: 'Описание поста2'},
        {id: 3, title: 'Javascript3', body: 'Описание поста3'},
      ]
    }
  }
}
</script>

<style> 
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.post {
  padding: 15px;
  border: 2px solid teal;
  margin-top: 15px;
}
</style>
