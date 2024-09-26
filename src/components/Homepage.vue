<script setup>
import { ref } from 'vue'
import headercard from './headercard.vue'
import IntroCard from './IntroCard.vue'
import Carouselcard from './Carouselcard.vue'
import Productivecard from './Productivecard.vue'
</script>

<template>
    <nav>
        <headercard />
    </nav>
    <div class="container">
        <IntroCard />
        <Carouselcard />
        <Productivecard />
    </div>
</template>

<style scoped>
.container{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 50px;
    margin: 0 100px;

}
</style>