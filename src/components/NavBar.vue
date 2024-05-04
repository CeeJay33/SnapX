<template>
    <div class="navigation">
        <div class="logo">
            <h2>Snap<span class="font">X</span></h2>
            <span class="undern">Lorem ipsum dolor </span>
        </div>
        <div class="navs">
            <ul class="links">
                <li>HOME</li>
                <select name="" id="">
                    <option value="">PHOTOS & VIDEOS</option>
                </select>
                <li>CATEGORIES</li>
                <li>USERS</li>
            </ul>
</div>
<div class="signup">
    <button><i class="fas fa-user"></i> Sign In/Up</button>
</div>

    </div>
</template>

<script>
export default {
  name: 'NavBar',
 
}

</script>

<style scoped>
.font{
    color: rgb(54, 211, 255);
}
.navigation{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.logo .undern{
    font-size: 12px;
}

.navs{
    background-color: rgb(0, 198, 252);
}

.navs .links{
    display: flex;
    gap: 3rem;
    padding: 1rem 1.5rem;
    list-style: none;
}

.navs .links li{
    font-size: 14px;
    font-weight: 600;
    color: #fff;
    cursor: pointer;
}

.navs .links select,option{
    border: none;
    background-color: transparent;
    font-size: 14px;
    font-weight: 600;
    color: #fff;
    cursor: pointer;

}

.signup button{
    background-color: transparent;
    padding: 7px 30px;
    color: rgb(54, 211, 255);
    border: 2px solid rgb(54, 211, 255);
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
}

</style>