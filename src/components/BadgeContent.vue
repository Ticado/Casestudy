<template>
  <div class="BadgeContent d-flex justify-center" >
    <slot />
  </div>
</template>

<style>
.BadgeContent {
  position: absolute;  
  text-align: center;
  color:#00504A;
  font-weight: bold;
  font-size: 20px;
  line-height: 19px;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%)
}
</style>