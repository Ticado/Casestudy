<template>
  <div class="LeftCardBadge d-flex justify-center" >
    <slot />
  </div>
</template>

<style>
.LeftCardBadge {
  background-color: transparent !important;
  display: flex;
  position: relative;
  height: 60px;
  top: -30px;
}

.LeftCardBadge__img {
position: absolute;
  left: 50%;
  transform: translate(-50%);
height: 60px;
  width: 60px;
  z-index: 3;
 background-size: cover;
}

.LeftCardBadge.Coin .LeftCardBadge__img {
  background-image: url('PNG/Coin.png') ;
  

}
</style>