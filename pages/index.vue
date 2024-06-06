<script setup lang='ts'>

import img1 from "@/assets/1.jpg"
import img2 from "@/assets/2.jpg"
import img3 from "@/assets/3.jpg"
import img4 from "@/assets/4.jpg"
import img5 from "@/assets/5.jpg"


</script>

<template>
    <section class="page">
        <h1>How to join the self hosted minecraft server</h1>
        <img :src=img1>
        <img :src=img2>
        <img :src=img3>
        <img :src=img4>

        <br>
        <br>
        <h2>Click on join server</h2>
        <img :src=img5>
    </section>

</template>

<style scoped>

*{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

h1{
    font-size: 42px;
}

h2{
    font-size: 24px;
}
.page {
    max-width: 1280px;
    padding: 1rem;
    margin: auto;
}

.page img {
    width: 100%;
    display: block;
    margin-top: 3rem;
}


h1, h2{
    text-align: center;
}
</style>