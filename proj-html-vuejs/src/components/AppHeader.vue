<template>
  <header>
    <section class="my_first_section">
        
          <img src="../assets/imgs/logo.png" alt="logo">
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
    <section class="my_second_section">
      <div class="my_first_box">
        <h1>
          Independent professional who works remotely to help with your business.
        </h1>
        <p>
          Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.
        </p>
        <div class="button-2">
        Buy Avada Now
      </div>
      </div>
      
      <div class="my_second_box">
          <img src="../assets/imgs/info-5.jpg" alt="info-5" class="header_img">
      </div>
      <button type="button" class="my_button_square_1">
        <i class="fa-solid fa-layer-group fa-xl"></i>
        Prebuilts
      </button>
      <button type="button" class="my_button_square_2">
        <i class="fa-solid fa-cart-shopping fa-xl"></i>
        Buy Now
      </button>
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
    background-image: url(../assets/imgs/home-bg-3.svg);
  background-position: bottom;
  background-size: 1700px;
  background-repeat: no-repeat;
 }

 .my_first_section{
    display: flex;
    align-items: center;
    background-image: url(../assets/imgs/header-bg.svg);
    background-repeat: no-repeat;
    background-size: auto;
    height: 70px;
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

.my_second_section{
  width: 100%;
  height: 550px;
  background-color: #0d1267;
  display: flex;
  padding: 3rem;
  justify-content: space-between;
  position: relative;
  z-index: 1;
  
}

.my_first_box{
  width: 50%;
  height: 100%;
  color: white;
  text-align: center;
  padding: 4rem;
}

.my_second_box{
  width: 50%;
  height: 100%;
  margin-left: 100px;
}

h1{
  font-size: 3rem;
}

p{
  font-size: 1.5rem;
  padding: 3rem;
}

.button-2 {
  background-color:white; 
  color: #000545;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}

.header_img{
  width: 520px;
}

.my_button_square_1{
  height: 70px;
  width: 70px;
  position: absolute;
  left: 1400px;
  background-color: white;
  border-radius: 20%;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  top: 20px;
}

.my_button_square_2{
  height: 70px;
  width: 70px;
  position: absolute;
  left: 1400px;
  background-color: white;
  border-radius: 20%;
  top: 100px;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}
</style>