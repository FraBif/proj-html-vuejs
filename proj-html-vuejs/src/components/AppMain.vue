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
</template>

<script>

</script>

<style scoped>
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
</style>