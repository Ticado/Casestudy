<template>
  <div class="BadgeImages d-flex justify-center" >
    <slot />
  </div>
</template>

<style>
.BadgeImages {
  background-color: transparent !important;
  display: flex;
  position: relative;
  height: 90px;
  top: -45px;
  margin-bottom: -15px;
}

.BadgeImages__img {
position: absolute;
  left: 50%;
  transform: translate(-50%);
height: 77px;
  width: 77px;
  z-index: 3;
 background-size: cover;
}

.BadgeImages.locked .BadgeImages__img {
  background-image: url('PNG/Badge_locked.png') ;
  

}

.BadgeImages.bronze .BadgeImages__img {
    background-image: url('PNG/Badge_bronze.png');
}

.BadgeImages.silver .BadgeImages__img {
   background-image: url('PNG/Badge_silver.png');

}

.BadgeImages.gold .BadgeImages__img {
  background-image: url("PNG/Badge_gold.png") ;
}

.BadgeImages.plat .BadgeImages__img {
  background-image: url("PNG/Badge_platinum.png") ;
}

.BadgeImages.bblue .BadgeImages__img {
  background-image: url("PNG/Badge_blue.png") ;
}


.BadgeImages.bred .BadgeImages__img {
  background-image: url("PNG/Badge_red.png") ;
}

.BadgeImages.bgreen .BadgeImages__img {
  background-image: url("PNG/Badge_green_eerste-keer-inloggen.png") ;
}

.BadgeImages.bpink .BadgeImages__img {
  background-image: url("PNG/Badge_pink_opleid.budget-inzetten.png") ;
}

.BadgeImages.bpurple .BadgeImages__img {
  background-image: url("PNG/Badge_purple_themas-afmaken.png") ;
}
</style>
