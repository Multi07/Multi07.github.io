<script setup>
  const links = [
    {name:"Home", url:"#"},
    {name:"About", url:"#about"},
    {name:"Projects", url:"#projects"},
    {name:"Gallery", url:"#gallery"},
  ]
</script>


<template>


  <div>
    <template v-for="link in links">
        <mybutton :link="link.url">{{ link.name }}</mybutton>
    </template>
    <h1>Hello world!</h1>
    <post>
    <template #title>Niggoerjnsadf</template>
    <template #secondtitle>trololol</template>
  </post>
    
    <a href="">ssdsd</a>
  </div>

  <section id="about">
    <h1>About me</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus quisquam iure assumenda nostrum, earum facilis natus cumque fuga eligendi, eveniet dignissimos similique laboriosam architecto possimus ut ea! Itaque, repellat reprehenderit?</p>
  </section>
</template>

<style scoped>

</style>