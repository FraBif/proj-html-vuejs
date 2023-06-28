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
     <div class="my_second_container">
        <div class="my_first_box">
            <h1>
                Independent professional who works remotely to help with your business.
            </h1>
            <div class="button-2">
                What is VA exactly?
            </div>
            <p>
                <i class="fa-regular fa-copyright fa-sm" style="color: #ffffff;"></i> Copyright 2012-2023|Avada Theme by <span class="orange">ThemeFusion</span>|All Rights Reserved|Powered by <span class="orange">WordPress</span>
            </p>
        </div>
        <div class="my_first_box"></div>
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

.my_second_container{
    display: flex;
    width: 93%;
    height: 300px;
    margin: auto;
}

.my_first_box{
    width: 50%;
    height: 100%;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    
} 

h1{
    font-size: 2.7rem;
}

.button-2 {
  background-color:white; 
  color: #000545;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  align-self: flex-start;
}

.orange{
    color: #eb6137;
}

span:hover{
    color: #eb6137;
}

.button-1:hover{
  background-color:white; 
  color: #000545;
}

.button-2:hover{
  background-color:#000545; 
  color: white;
}

.orange:hover{
    color: white;
}
</style>