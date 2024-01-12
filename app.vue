<script setup>
  const links = [
    {name:"Home", url:"/"},
    {name:"About", url:"/about"},
    {name:"Projects", url:"/projects"},
    {name:"Gallery", url:"/gallery"},
  ]
</script>


<template>


  <div>
    <template v-for="link in links">
        <mybutton :link="link.url">{{ link.name }}</mybutton>
    </template>
    <h1>Hello world!</h1>
    <post>
    <template #title>Nierjnsadf</template>
    <template #secondtitle>trololol</template>
  </post>
    
    <a href="">ssdsd</a>
  </div>

 <NuxtPage>

 </NuxtPage>
</template>
<style scoped>

</style>