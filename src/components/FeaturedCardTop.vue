<template>
    <div class="FeaturedCardTop">
        <slot/>
    </div>
</template>

<style>
.FeaturedCardTop {
    font: normal normal bold 16px/19px Open Sans;
    color: white;
    text-align: center;
    background: #00504A 0% 0% no-repeat padding-box;
    border-radius: 0px 10px 10px 10px;
    height:77px;
}

.FeaturedCardTop.locked .FeaturedCardTop__img {
background: url("PNG/Mask Group 7.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.bronze .FeaturedCardTop__img {
background: url("PNG/BG-badge-red.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.silver .FeaturedCardTop__img {
background: url("PNG/BG-badge-grey.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.gold .FeaturedCardTop__img {
background: url("PNG/BG-badge-blue.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.plat .FeaturedCardTop__img {
background: url("PNG/BG-badge_platinum.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.blue .FeaturedCardTop__img {
background: url("PNG/BG-badge-realblue.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.red .FeaturedCardTop__img {
background: url("PNG/BG-badge-realred.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.green .FeaturedCardTop__img {
background: url("PNG/BG-badge-green.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.pink .FeaturedCardTop__img {
background: url("PNG/BG-badge-pink.png") center center;
background-size: cover;
width:100%;
height: 100%;
}

.FeaturedCardTop.purple .FeaturedCardTop__img {
background: url("PNG/BG-badge-realpurple.png") center center;
background-size: cover;
width:100%;
height: 100%;
}




</style>