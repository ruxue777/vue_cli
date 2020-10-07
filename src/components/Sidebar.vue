<template>
  <ul class="link">
      <li v-for="(item,index) in link" :key="index"><a href="#">{{item}}</a></li>
  </ul>
</template>

<script>
export default {
    name: 'Sidebar',
    data() {
        return {
            link:['首页','图文','咨询','关于']
        }
    }
}
</script>

<style scoped>
.link a{
    color: brown;
}
</style>