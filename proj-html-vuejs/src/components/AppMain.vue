<template>
 <section class="my_first_section">
    <h2>
        Available services
    </h2>
    <div class="my_cards_container">
        <div class="my_card" id="borderless">
            <h1>
                Answering phone calls
            </h1>
            <p>
                Elementum posuere mauris, ac ultricies eu orci massa at id tincidunt
            </p>
        </div>
        <div class="my_card">
            <h1>
                Basic data entry
            </h1>
            <p>
                Elementum posuere mauris, ac ultricies eu orci massa at id tincidunt
            </p>
        </div>
        <div class="my_card">
            <h1>
                Organizing calendar
            </h1>
            <p>
                Elementum posuere mauris, ac ultricies eu orci massa at id tincidunt
            </p>
        </div>
        <div class="my_card">
            <h1>
                Booking travels
            </h1>
            <p>
                Elementum posuere mauris, ac ultricies eu orci massa at id tincidunt
            </p>
        </div>
    </div>
    <div class="my_second_container">
       <div class="my_box">
        <img src="../assets/imgs/info-5-2x.png" alt="info_2" class="my_img_1">
       </div>
       <div class="my_box_2">
       <img src="../assets/imgs/icon-1-2x.png" alt="icon" class="icon_1">
       <h1 class="my_title">
        Find the ultimate virtual assistant for your business
       </h1>
       <p>
        Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula.
       </p>
       <button type="button" class="button-1">
        What is a VA exactly?
       </button>
       </div>
    </div>
 </section>
 <section class="my_second_section">
   <div class="my_third_box">
    <h3>
        Donec est tristique eu massa pellentesque.
    </h3>
    <h1 class="my_h1">
        Highly-skilled, independent professional freelancer.
    </h1>
    <button type="button" class="button-2">
        Buy Avada now
       </button>    
   </div>
   <div class="my_fourth_box">
      <div class="my_card_2">
        <div class="part_1">
            <span class="number">
                1.
            </span>
        </div>
        <div class="part_2">
            <p class="my_desc">
                Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.
            </p>
            <p class="my_desc link">
                Learn more
            </p>
        </div>
      </div>
      <div class="my_card_2">
        <div class="part_1">
            <span class="number">
                2.
            </span>
        </div>
        <div class="part_2">
            <p class="my_desc">
                Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.
            </p>
            <p class="my_desc link">
                Learn more
            </p>
        </div>
      </div>
      <div class="my_card_2">
        <div class="part_1">
            <span class="number">
                3.
            </span>
        </div>
        <div class="part_2">
            <p class="my_desc">
                Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.
            </p>
            <p class="my_desc link">
                Learn more
            </p>
        </div>
      </div>
   </div>
 </section>
 <section class="my_third_section">
    <h3 id="brands">
        Trusted by this amazing brands
    </h3>
    <div class="flex my_brand_container">
        <img src="../assets/imgs/brand-1.jpg" alt="brand-1">
        <img src="../assets/imgs/brand-3.jpg" alt="brand-2">
        <img src="../assets/imgs/brand-4.jpg" alt="brand-3">
        <img src="../assets/imgs/brand-5.jpg" alt="brand-4">
        <img src="../assets/imgs/brand-7.jpg" alt="brand-5">
    </div>
    <div class="my_fifth_box">
         <div class="my_card_3">
           <img src="../assets/imgs/icon-2-2x.png" alt="icon-2" class="icon_2">
           <h1 class="my_title">
            Professional who works to help with your business.
           </h1>
           <p>
            Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula.
           </p>
           <button class="button-1">
            What is VA exactly?
           </button>
         </div>
         <div class="my_card_4">
            <img src="../assets/imgs/info-8-2x.png" alt="info-5" class="info_5">
         </div>
    </div>
    <div class="my_sixth_box">
        <div class="my_card_5">
            <div class="part_3" id="bground">
               <span class="number">
                  1.
               </span>
            </div>
            <div class="part_4">
                 <h3>
                    Learn to delegate
                 </h3>
                 <p>
                    Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.
                 </p>
                 <span class="link">
                    Learn more
                 </span>
            </div>
        </div>
        <div class="my_card_5">
            <div class="part_3">
               <span class="number">
                  2.
               </span>
            </div>
            <div class="part_4">
                 <h3>
                    Reduce labor costs
                 </h3>
                 <p>
                    Mauris aliquam libero, fermentum quis eros, massa sagittis. Lectus mattis elit purus venenatis.
                 </p>
                 <span class="link">
                    Learn more
                 </span>
            </div>
        </div>
    </div>
 </section>
</template>

<script>

</script>

<style scoped>
.flex{
    display: flex;
}
.my_first_section{
    padding: 5rem;
}

h2{
    color: #f86635;
}

.my_cards_container{
    width: 1400px;
    height: 350px;
    margin-right: 30px;
    margin-top: 40px;
    display: flex;
    border-top: 1px gray solid;
}

.my_card{
    height: 100%;
    width: calc(100% / 4);
    border-left: 1px grey solid;
    padding: 3rem;
    color: #0d1267;
}

h1{
    font-size: 2.5rem;
}

p{
    margin-top: 20px;
    font-size: 1.5rem;
    line-height: 35px;
}

#borderless{
    border-left: white 1px solid;
}

.my_second_container{
    width: 1300px;
    height: 700px;
    margin-right: 50px;
    margin-top: 100px;
    margin-left: 40px;
    display: flex;
}

.my_box{
    width: calc(100% / 2);
    height: 100%;
    display: flex;
    flex-direction: column;
    color: #0d1267;
    text-align: center;
    align-items: center;
}

.my_box_2{
    width: calc(100% / 2);
    height: 100%;
    display: flex;
    flex-direction: column;
    color: #0d1267;
    text-align: center;
    align-items: center;
    padding: 3rem;
    padding-top: 6rem;
}

.my_img_1{
    width: 700px;
}

.icon_1{
    width: 200px;
}

.my_title{
    margin-top: 3rem;
    font-size: 3rem;
}

.button-1 {
  background-color:#f86635; 
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-top: 50px;
}

.my_second_section{
    width: 100%;
    height: 1000px;
    background-color: #0d1267;
    position: relative;
    background-image: url(../assets/imgs/info-bg-3.svg);
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: 1800px;
}

.my_third_box{
    color: white;
    margin: auto;
    text-align: center;
    padding: 9rem;
    position: relative;
  
}

h3{
    font-size: 1.5rem;
}

.my_h1{
    font-size: 4rem;
    padding: 5rem;

}

.button-2 {
  background-color:#f86635; 
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-top: 50px;
  position: absolute;
  top: 400px;
  right: 675px;
}

.my_fourth_box{
    width: 100%;
    height: 40%;
    background-color: #0d1267;
    display: flex;
    justify-content: space-around;
    padding: 3rem;
    position:absolute;
    bottom: 90px;
}

.my_card_2{
    width: 30%;
    height: 95%;
    background-color: #000545;
    display: flex;
    color: white
}

.part_1{
    width: 30%;
    height: 100%;
    padding: 3rem;
}

.part_2{
    width: 70%;
    height: 100%;
    padding: 2rem;
}

.number{
    font-size: 3.5rem;
}

.my_desc{
    font-size: 1.3rem;
}

.link{
    color: #f86635;
    text-decoration: underline;
}

#brands{
    color: #f86635;
    text-align: center;
    margin-top: 80px;
}

.my_brand_container{
    padding: 1.5rem;
}

.my_fifth_box{
    margin: auto;
    width: 80%;
    height: 700px;
    display: flex;
}

.my_card_3{
    height: 100%;
    width: 50%;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 2rem;
}

.my_card_4{
    height: 100%;
    width: 50%;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.icon_2{
    width: 200px;
}

.info_5{
    width: 700px;
}

.my_sixth_box{
    width: 90%;
    height: 400px;
    display: flex;
    margin: auto;
    justify-content: space-around;
    margin-top: 100px;
}

.my_card_5{
    width: 40%;
    height: 80%;
    display: flex;
    color: white;
    background-color: #000545;
}

.part_3{
    height: 100%;
    width: 30%;
    padding: 3rem;
}

.part_4{
    height: 100%;
    width: 70%;
    padding: 3rem;
    display: flex;
    flex-direction: column;
    align-content: center;
    justify-content: space-between;
}

.button-1:hover{
    background-color: #0d1267;
}

.button-2:hover{
    background-color: #0d1267;
}

#bground{
    background-image: url(../assets/imgs/box-bg-1.svg);
    background-size: 800px;
    background-position: bottom left;
    background-repeat: no-repeat;
}
</style>