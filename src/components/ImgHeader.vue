<template>
    <div class="img-header">
        <div class="content-text">
            <p class="text-img">Bienvenido a mi <span>web</span></p>
        </div>
        <div class="content-vacio"></div>
    </div>
</template>

<script setup></script>

<style scoped lang="scss">
.img-header {
    display: flex;
    height: 730px;
    justify-content: center;
    align-items: center;
    align-self: stretch;
    background: linear-gradient(0deg, rgba(53, 73, 94, 0.30) 0%, rgba(53, 73, 94, 0.30) 100%), url('../assets/images/imgheader.png'), lightgray 50% / cover no-repeat;
}
.content-text {
    display: flex;
    padding: 10px 10px 10px 25px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    flex: 1 0 0;
    align-self: stretch;
}
.content-vacio {
    display: flex;
    padding: 10px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    flex: 1 0 0;
    align-self: stretch;
}
.text-img {
  color: #FFF;
  font-family: InterExtraBold;
  font-size: 70px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  align-self: stretch;
}
span {
    color: #F34C00;
}
</style>