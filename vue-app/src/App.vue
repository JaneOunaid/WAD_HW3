<template>
 <div>
   <my-header></my-header>
   <my-footer></my-footer>
 </div>
</template>

<script>
import Header from './components/Header';
import Footer from './components/Footer';
  export default {
     components:{
         'my-header':Header,
         'my-footer':Footer,
     }
  }
</script>

<style>
  *{
      box-sizing:border-box;
      margin:0;
  }
</style>