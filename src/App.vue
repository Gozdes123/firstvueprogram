
<template>
 <!-- <router-link to="/">Home</router-link> | -->
 <div>
     <NavBar/>
     <MyCarousel/>
 </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import MyCarousel from "./components/MyCarousel.vue";
export default {
name:'App',
components:{
  NavBar,MyCarousel
}
}
</script>

<style>

</style>
