<template>
  <header>
    <section class="my_first_section">
        
          <img src="../assets/desktop version img/logo.png" alt="logo">
          <HeaderNav/>  
          <div class="sidebar">
            <span>
                <i class="fa-solid fa-headphones fa-xl" style="color: #ffffff;"></i>
                1.800.123.4567
            </span>
          </div>
          <div class="button-1">
             Get a free consultation
          </div>

        
        
    </section>
  </header>
</template>

<script>
  import HeaderNav from './HeaderNav.vue';
  export default {
        components: {
            HeaderNav,
        },
        data() {
            return {
                
            }
        },
        created() {
            
        },
        mounted() {
            
        },
        props: {
        },
        computed: {
            
        },
        methods: {
            
        },
    }
</script>

<style scoped>
 header{
    background-color: #0d1267;
    width: 100%;
    padding: 3rem;
 }

 .my_first_section{
    display: flex;
    align-items: center;
    background-image: url(../assets/);
 }

 .sidebar{
    color: white;
    font-size: 1.3rem;
    margin-left: 370px;
 }

 .button-1 {
  background-color:white; 
  color: #000545;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-left: 100px;
}
</style>