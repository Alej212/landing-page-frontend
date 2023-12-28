<template>
    <section class="section-stack">
        <h2>Stack</h2>
        <div class="cards-content">
            <div class="card">
                <h3>Frontend</h3>
                <div class="icons-content">
                    <SectionStackIconsF></SectionStackIconsF>
                </div>
            </div>
            <div class="card">
                <h3>Backend</h3>
                <div class="icons-content">
                    <SectionStackIconsB></SectionStackIconsB>
                </div>
            </div>
        </div>
        <div>
            <p class="name-icons">Icon</p>
        </div>
    </section>
</template>

<script setup>
import SectionStackIconsF from './SectionStackIconsF.vue';
import SectionStackIconsB from './SectionStackIconsB.vue';
</script>

<style scoped lang="scss">
.section-stack {
    display: flex;
    padding: 80px 10px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 60px;
    align-self: stretch;
}
.cards-content {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
}
.card {
    display: flex;
    width: 340px;
    height: 400px;
    padding: 30px 30px 60px 30px;
    flex-direction: column;
    align-items: center;
    gap: 50px;
    border-radius: 5px;
    background: var(--Foundation-Red-Lighter, #FAAE8C);
}
.icons-content {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    align-content: flex-start;
    gap: 30px;
    align-self: stretch;
    flex-wrap: wrap;
}
.name-icons {
    color: var(--Foundation-Red-Normal, #F34C00);
    font-family: InterBold;
    font-size: 25px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}
</style>