<template>
       
        <RouterView />
        <Navbar/>
         <Footer/>
</template>
<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
  export default{
    name:'App',
    components:{
        Navbar,
        Footer
        

    }
  }
</script>
<style>
body{
 background-color: rgb(112, 103, 165);

}
</style>