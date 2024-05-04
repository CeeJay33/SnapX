<template>
    <div class="pro_page">
        <span class="fontss">CLOSED PHOTOGRAPH CONTEST</span>
        <h2><span class="font">Previous Contests</span> With Handpicked <span class="font">Winners</span></h2>
        <div class="containerr">
            <div class="imagee">
                
                <img src="../assets/brunette_sunset_hat_women_outdoors_long_hair_sunlight_sunglasses_women_with_glasses-207554.jpg" alt="">
                <div class="monn">
        <div class="mon">
            <p>96 Participants</p>
            <span>Number Of Artists</span>
        </div>
        <div class="mon">
            <p>410 Pictures</p>
            <span>Submitted Pics</span>
        </div>
    </div>
            </div>
            <div class="imagee">
                <img  src="../assets/401747_23029_XL.jpg" alt="">
                <div class="monn">
        <div class="mon">
            <p>74 Participants</p>
            <span>Number Of Artists</span>
        </div>
        <div class="mon">
            <p>256 Pictures</p>
            <span>Submitted Pics</span>
        </div>
    </div>
</div>
<div class="imagee">
    <img src="../assets/IMG-20200121-WA0058.jpg" alt="">

    <div class="monn">
        <div class="mon">
            <p>88 Participants</p>
            <span>Number Of Artists</span>
        </div>
        <div class="mon">
            <p>320 Pictures</p>
            <span>Submitted Pics</span>
        </div>
    </div>
</div>

        </div>
        <div class="button">
            <button class="btnn">Browse Open Contests</button>
        </div>
   </div>
</template>

<script>
  export default {
  name: 'ProPage',
 
}


</script>

<style>
.pro_page{
    margin-top: 5rem;
    padding: 5rem 0;
    background-color: rgb(237, 253, 253);
}

.fontss{
    font-size: 10px;
    font-weight: 600;
    margin-bottom: 3px;
    color: rgb(54, 211, 255);
}

.containerr{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 16px;
}

.containerr .imagee{
    width: 320px;
    height: 285px;
    background-color: #fff;
    margin-top: 30px;
    border-top-left-radius: 9px;
    border-top-right-radius: 9px;
}

.containerr .imagee img{
    width: 100%;
    height: 200px;
    border-top-left-radius: 9px;
    border-top-right-radius: 9px;
}

.imagee .monn{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 19px;
}

.imagee .monn p{
    font-weight: 700;
    opacity: 0.9;
}

.imagee .monn span{
    font-size: 13px;
    opacity: 0.5;
}

.btnn{
    background-color: transparent;
    padding: 7px 30px;
    color: rgb(54, 211, 255);
    border: 2px solid rgb(54, 211, 255);
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    margin-top: 10px;
}

</style>