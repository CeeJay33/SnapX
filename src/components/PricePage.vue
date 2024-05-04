<template>
    <div class="price_page">
        <span class="fontss">OUR PRICING</span>
        <h2>Photography <span class="font">Contest Plans</span> And Price <span class="font">Awards</span></h2>
    <div class="listing">
        <div class="con_1">
            <img src="../assets/WhatsApp_Image_2024-03-08_at_08.53.58_0aedbf2a-removebg-preview.png" alt="">
            <h3>Basic Plan</h3>
            <hr noshade size="1px" width="80%">
            <div class="font_info">
                <p class="font">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
            </div>
            <span>Digital Photograph Awards</span>
            <div class="price">
                <h2 class="font">$25 USD</h2>
            </div>
            <div class="button">
            <button class="btnn">Choose This Plan</button>
        </div>
        </div>
        <div class="con_1">
            <img src="../assets/WhatsApp_Image_2024-03-08_at_08.53.58_0aedbf2a-removebg-preview.png" alt="">
            <h3>Standard Plan</h3>
            <hr noshade size="1px" width="80%">
            <div class="font_info">
                <p class="font">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
            </div>
            <span>Digital Photograph Awards</span>
            <div class="price">
                <h2 class="font">$45 USD</h2>
            </div>
            <div class="button">
            <button class="btnn">Choose This Plan</button>
        </div>
        </div>
        <div class="con_1">
            <img src="../assets/WhatsApp_Image_2024-03-08_at_08.53.58_0aedbf2a-removebg-preview.png" alt="">
            <h3>Advance Plan</h3>
            <hr noshade size="1px" width="80%">
            <div class="font_info">
                <p class="font">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
            </div>
            <span>Digital Photograph Awards</span>
            <div class="price">
                <h2 class="font">$85 USD</h2>
            </div>
            <div class="button">
            <button class="btnn">Choose This Plan</button>
        </div>
        </div>
    </div>
    </div>
</template>


<style>
hr{
    margin: 4px auto;
    border: 1px solid #ededed;
}
.price_page{
    margin-top: 5rem;
}

.listing{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 25px;
    margin-top: 25px;
}

.listing .con_1{
    height: auto;
    width: 260px;
    border: 1px solid #e8e8e8;
    border-radius: 7px;
    padding: 10px 0;
}

.con_1 img{
    width: 50%;
    height: 80px;
}

.con_1 h3{
    padding: 6px 0;
}

.font_info{
    width: 50%;
    margin:6px auto;
}

.font_info p{
    line-height: 30px;
    font-size: 14px;
}

.con_1 span{
    font-size: 12px;
    font-weight: 600;
    opacity: 0.7;
}

.price{
    margin: 15px 0;
}
</style>