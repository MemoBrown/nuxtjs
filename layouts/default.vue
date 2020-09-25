<template>
<div>
  <Navigation />
  <div>
    <Nuxt />
  </div>
</div>

</template>

<script>
import Navigation from '@/components/Navigation'
export default {
  components: {
    Navigation
  }
}
</script>

<style>
  *{
    box-sizing: border-box;
    color: whitesmoke;
    margin: 0;
    padding: 0;
  }
  html{
    font-size: 62.5%;
  }
  body{
    background: #2d3436;
    color: whitesmoke;
    font-family: Arial, Helvetica, sans-serif;
    padding: 0;
  }
  .content{
    padding: 2rem
  }
</style>
