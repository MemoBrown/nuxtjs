<template>
  <div class="card">
    <h2>{{ post.title }}</h2>
    <p>ID: {{ post.id }}</p>
    <p>{{ post.userId }}</p>
    <p>Content:<br> {{ post.body }}</p>
  </div>
</template>

<script>
import axios from 'axios'

export default {

  data() {
    return {
      post: {}
    }
  },

  async created() {
    const res = await axios.get(`https://jsonplaceholder.typicode.com/posts/${this.$route.params.id}`)
    this.post = res.data;
  }
}
</script>

<style scoped>
  .card{
    margin: 2rem;
    border: 1px solid whitesmoke;
    padding: 4rem;
    font-size: 1.8rem;
  }
</style>