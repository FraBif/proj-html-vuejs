<template>
  <footer>
     <div class="my_first_container">
        <img src="../assets/imgs/logo.png" alt="logo">
          <HeaderNav/>  
          <div class="sidebar">
            <span>
                <i class="fa-solid fa-headphones fa-xl" style="color: #ffffff;"></i>
                1.800.123.4567
            </span>
          </div>
          <div class="button-1">
             Buy Avada now
          </div>
     </div>
  </footer>
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
footer{
    background-color: #0d1267;
}
 .my_first_container{
    display: flex;
    align-items: center;
    padding: 3rem;
 }

 .sidebar{
    color: white;
    font-size: 1.3rem;
    margin-left: 370px;
 }

 .button-1 {
  background-color:#000545; 
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-left: 100px;
}
</style>