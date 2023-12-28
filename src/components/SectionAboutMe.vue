<template>
    <div class="section-about-me">
        <div class="content-text">
            <h2>About me</h2>
            <p class="paragraph">
                Soy un desarrollador Full Stack con experiencia en el diseño, desarrollo, implementación y pruebas de aplicaciones. Mis lenguajes favoritos para programar son JavaScript y Python. Mis habilidades abarcan tanto el frontend, con la creación de interfaces de usuario en Figma, como el backend, con la creación de APIs robustas y escalables. Además, realizo pruebas en mis aplicaciones para garantizar su correcto funcionamiento.
            </p>
        </div>
        <div class="content-animation"></div>
    </div>
</template>

<script setup></script>

<style scoped lang="scss">
.section-about-me {
    display: flex;
    padding: 10px;
    align-items: center;
    gap: 30px;
    align-self: stretch;
    background-color: #fff;
}
.content-text {
    display: flex;
    height: 612px;
    padding: 80px 10px 0px 20px;
    flex-direction: column;
    align-items: flex-start;
    gap: 30px;
    flex: 1 0 0;
}
.paragraph {
    color: #000;
    font-family: Inter;
    font-size: 18px;
    font-style: normal;
    font-weight: 500;
    line-height: 24px; /* 133.333% */
    align-self: stretch;
}
.content-animation {
    display: flex;
    height: 612px;
    padding: 10px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    flex: 1 0 0;
}
</style>