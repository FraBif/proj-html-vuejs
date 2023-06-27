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
</style>