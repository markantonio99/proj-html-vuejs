 <template>
    
    <Header />  
    <Main />  
    <Home3 />
    <Home4 />
    <Home5 />
    <Home6 />
    <Footer />
   
 </template>
 
 <script>
 import Header from './components/Header.vue';
 import Main from './components/Main.vue';
 import Footer from './components/Footer.vue';
 import Home3 from './components/Home3.vue';
 import Home4 from './components/Home4.vue';
 import Home5 from './components/Home5.vue';
 import Home6 from './components/Home6.vue';
 
 export default {

  components:{
    Header,
    Main,
    Footer,
    Home3,
    Home4,
    Home5,
    Home6,
  }
 }
 
 </script>
 
 <style lang="scss">
 @use './style/general.scss';
 
 </style>
