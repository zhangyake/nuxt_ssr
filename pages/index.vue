<template>
  <section class="container">
  <img src="/logo.jpg" alt="" srcset="">
  <ul>
       <li><nuxt-link :to="{name:'blog'}">我的博客</nuxt-link></li>
      <!-- <li><nuxt-link :to="{name:'about'}">ABOUT</nuxt-link></li>
      <li><nuxt-link :to="{name:'ansyData'}">ansydata</nuxt-link></li>
      <li><nuxt-link :to="{name:'news',params:{newsId:3306}}">NEWS</nuxt-link></li>
      <li><nuxt-link :to="{name:'news-id',params:{id:123,title:'my blog'}}">News-1</nuxt-link></li> -->
    </ul>

  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  /* background-image: url('/logo.jpg') ; */
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
