<template>
    <div class="BottomShape">
        <slot/>
    </div>
</template>
<style scoped>
.BottomShape--left{
    z-index: 2;
    background: #6dc8bf 0% 0% no-repeat padding-box;
    border-radius: 80px 80px 0px 0px;
    height: 200px;
    width: 90%;
    opacity: 0.2;
}
.BottomShape--right{
    z-index: 1;
    background: #095c4a 0% 0% no-repeat padding-box;
    border-radius: 80px 0px 0px 0px;
    height: 160px;
    width: 70%;
    margin-top: -160px;
    margin-bottom: 0px;
    float: right;
    opacity: 1;
}
</style>