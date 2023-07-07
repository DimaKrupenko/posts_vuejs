<template>
  <div>
    <form>
      <h4>Создание поста</h4>
      <input type="text" placeholder="Название">
      <input type="text" placeholder="Описание">
      <button>Создать</button>
    </form>
    <div class="post" v-for="post in posts">
      <div><strong>Название:</strong> {{ post.title }}</div>
      <div><strong>Описание:</strong> {{ post.body }}</div>
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
