<template>
<div>
  <h1>Hello world</h1>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum quae praesentium iste voluptatum? Ut quis eaque error repudiandae unde incidunt, voluptates alias, laborum, modi cum minus quo quidem! Odit, ea.</p>
</div>
</template>

<script>
export default {
    head(){
    return {
      title: 'Application Nuxt | About',
      meta: [
        {
        hid: 'description',
        name: 'description',
        content: 'website about posts'
      }
      ],
      htmlAttrs: {
        lang: 'en'
      }
    }
  }

}
</script>