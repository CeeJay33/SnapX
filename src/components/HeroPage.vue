<template>
    <div class="hero_page">
        <h2>Enter a world of <span class="font">Photos</span> & Amazing <span class="font">Awards</span></h2>
        <hr noshade width="60%" size="1">
        <span class="span">Lorem ipsum dolor sit amet consectetur adipisicing elit. tyuje tit praesentium ab voluptatem numquam iste.</span>
        <div class="buttons">
            <button class="btn1">Explore snapX content</button>
            <button class="btn2"> <i class="fas fa-play"></i> Watch our Video now</button>
        </div>

        <div class="container">
            <div class="icon">
                <i class="fas fa-arrow-left"></i>
            </div>
            <div class="image">
                <img src="../assets/401747_23029_XL.jpg" alt="">
            </div>
            <div class="image">
                <div class="about">
                <h4>Walk In The Nature <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><span class="fon"> (4.5)</span></h4>
                    <div class="contestt">
                <h5>Contest Winner: <span class="fon">Thomas Eddy</span></h5>
                <h5>Contest Winner: <span class="fon">Anthony Soft</span></h5>
                <h5>Awards: <span class="fon">$8,400 + Canon EOS R1</span></h5>
                </div>
                </div>

                <!-- <h5>Contest Winner: <span>Thomas Eddy</span></h5>
                <h5>Contest Winner: <span>Anthony Soft</span></h5>
                <h5>Awards: <span>$8,400 + Canon EOS R1</span></h5> -->
</div>
<div class="image">
    <img src="../assets/clients-say.jpg" alt="">
</div>
<div class="icon">
                <i class="fas fa-arrow-right"></i>
            </div>
        </div>
    </div>

</template>

<script>
  export default {
  name: 'HeroPage',
 
}


</script>

<style>
hr{
   text-align: center;
}
.hero_page{
    background-image: linear-gradient(rgba(0, 0, 0, 0.731), rgba(0, 0, 0, 0.68)), url(../assets/Lilly.jpg);
 background-size: cover;
 background-repeat: no-repeat;
 height: 100vh;
 display: flex;
 flex-direction: column;
 justify-content: center;
 align-items: center;
 position: relative;

}

.hero_page h2{
    color: #fff;
    font-size: 40px;
    width: 60%;
    text-align: center;
    margin-bottom: 2rem;
}

.hero_page .span{
    color: #ccc;
    width: 50%;
    text-align: center;
    margin-top: 2rem;
}

.image .about{
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.image .about h4,i{
    color: rgb(0, 198, 252);
}

.image .contestt{
    margin-top: 15px;
}
.image .fon{
    color: #b2b1b1;
}

.image h5{
    font-weight: 700;
    font-size: 15px;
    line-height: 30px;
}
.font{
    color: rgb(0, 198, 252);
}

.buttons{
    margin-top: 2.5rem;
    display: flex;
    gap: 2.5rem;
}

.buttons button{
    background-color: transparent;
    cursor: pointer;

}

.buttons .btn1{
    color: #ccc;
    border: 2px solid #ccc;
    font-weight: 600;
    padding: 7px 13px;
    border-radius: 3px;
}


.buttons .btn2{
    color: #ccc;
    border: none;
    font-weight: 600;
    padding: 7px 13px;
}

.container{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
    position: absolute;
    bottom: -120px;
}
.container .image{
    width: 360px;
    height: 230px;
    border-radius: 10px;
    background-color: #ebebeb;
}

.container .image:hover{
    transform: translateY(-10px);
    transition: 0.2s all ease-in;
}

.container .image img{
    width: 360px;
    height: 230px;
    border-radius: 10px;

}

.icon .fas{
    background-color: rgb(0, 198, 252);
    padding: 9px 10px;
    color: #fff;
    border-radius: 50%;
    cursor: pointer;
}
</style>