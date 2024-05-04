<template>
    <div class="show_page">
    <div class="descript">
        <div class="des1">
            <span class="fonts">OUR CATEGORIES</span>
            <h2>Check Out <span class="font">Popular</span> Contest <span class="font">Categories</span></h2>
        </div>
        <div class="des2">
            <button>Discover All Categories</button>
        </div>
    </div>
    <div class="containers">
        <div class="image">
            <div class="desc">
        <div class="img">
            <img class="imgg"  src="../assets/picture.png" alt="">
        </div>
        <div class="gibb">
            <h3>Nature Pic Contest</h3>
            <div class="sub">
                <p>126</p>
                <span>Available Contest</span>
            </div>
        </div>
    </div>
                <img src="../assets/11-15-1024x683.jpg.optimal.jpg" alt="">
                <button class="btnn">Browse Nature Pic Contests</button>
            </div>
            <div class="image">
                <div class="desc">
        <div class="img">
            <img class="imgg"  src="../assets/camera.png" alt="">
        </div>
        <div class="gibb">
            <h3>Random Pic Contest</h3>
            <div class="sub">
                <p>116</p>
                <span>Available Contest</span>
            </div>
        </div>
    </div>
                <img src="../assets/Blackbuck_male_female.jpg" alt="">
                <button class="btnn">Browse Random Pic Contests</button>
            </div>
            <div class="image">
                <div class="desc">
        <div class="img">
            <img class="imgg"  src="../assets/camera-focus.png" alt="">
        </div>
        <div class="gibb">
            <h3>Potrait Pic Contest</h3>
            <div class="sub">
                <p>144</p>
                <span>Available Contest</span>
            </div>
        </div>
    </div>
                <img  src="../assets/bangladesh-4690975_640.jpg" alt="">
                <button class="btnn">Browse Potrait Pic Contests</button>
</div>
<div class="image">
    <div class="desc">
        <div class="img">
            <img class="imgg" src="../assets/flip.png" alt="">
        </div>
        <div class="gibb">
            <h3>Space Pic Contest</h3>
            <div class="sub">
                <p>135</p>
                <span>Available Contest</span>
            </div>
        </div>
    </div>
    <img src="../assets/hong-kong-sunny-bay-sunset.jpg" alt="">
    <button class="btnn">Browse Space Pic Contests</button>
</div>

        </div>
        </div>
</template>







<style>

.show_page{
    padding-top: 15rem;
}

.fonts{
    font-size: 10px;
    color: rgb(54, 211, 255);
    font-weight: 600;
}

.descript{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 2.5rem;
}
.descript .des1{
    text-align: left;
    padding-left: 30px;
}
.descript .des2 button{
    background-color: rgb(14, 169, 211);
    padding: 7px 20px;
    color: #fff;
    border: 2px solid rgb(14, 169, 211);
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    margin-right: 20px;
}
.containers{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
}

.containers .image{
   border: 1px solid rgb(224, 224, 224);
   width: 280px;
   border-radius: 7px;
   padding: 20px 0;
}

.containers .image img{
    width: 240px;
    height: 150px;
    border-radius: 7px;
    margin-top: 10px;

}

.containers .image button{
    background-color: transparent;
    padding: 7px 30px;
    color: rgb(54, 211, 255);
    border: 2px solid rgb(54, 211, 255);
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    margin-top: 10px;
}

.containers .image .desc{
    display: flex;
    align-items: center;
    justify-content: center;
}

.image .gibb .sub{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
}
.image .gibb .sub p{
    color: rgb(54, 211, 255);
    font-size: 13px;
    border: 1px solid rgb(224, 224, 224);
    padding: 2px 3px;
    margin-left: 10px;
}
.image .gibb .sub span{
    font-size: 14px;
    color: rgb(197, 195, 195);
}
.image .gibb h3{
   font-size: 15px;
   margin-bottom: 5px;
}

.containers .image  .imgg{
    width: 30px;
    height: 25px;
    background-color: #f1f1f1;
    padding: 15px 10px;
}
</style>