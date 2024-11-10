<script setup lang='ts'>

import img1 from "@/assets/1.jpg"
import img2 from "@/assets/2.jpg"
import img3 from "@/assets/3.jpg"
import img4 from "@/assets/4.jpg"
import img5 from "@/assets/5.jpg"


</script>

<template>
    <section class="page">
        <h1>Welcome to our server</h1>
        <p>Here you can find the instructions on how to join our self hosted minecraft server</p>
        <!-- <p class="note"><b>Note:</b> Please read the below rules first before joining the server</p> -->

        <!-- <br>
        <h2>Minecraft Server Rules</h2>
        <div class="rules">
            <h3>1. Base Protection:</h3>
            <ul>
                <li>
                    No one is allowed to <b>break</b> or <b>damage</b> any part of the <b>opponent's base</b>
                    structure.
                </li>

                <li>
                    Do not <b>kill</b> any living organism (players, animals, or mobs) inside the <b>opponent's
                        base</b>.
                </li>
            </ul>

            <h3>2. Base Construction Requirement:</h3>
            <ul>
                <li>Each team must <b>fully enclose</b> their base with a <b>wall</b>. The base will be <b>considered illegal</b> and subject
                    to <b>no violation rule applicable</b> if it is not properly covered.</li>
            </ul>

            <h3>3. Consequences for Rule Violation:</h3>
            <ul>
                <li>If you <b>violate</b> any of the above rules, you will be <b>killed</b> by the admin or <b>opponent player</b> and you will get looted.</li>
                <li>Upon violation, your game progress will be reset by the admin, and you will be placed in <b>"Visitor"</b>
                    mode for one day if you <b>opposed</b> to get looted, meaning you won't be able to interact with the world.</li>
            </ul>

            <h3>4. Teams:</h3>
            <ul>
                <li>There are two teams: <b>God Slayer</b> and <b>The Deathbound</b>.</li>
                <li>God Slayer members: <b>Senpai</b>, <b>Killerbro</b>, <b>Rohan</b> or others.</li>
                <li>The Deathbound members: <b>Niteshdev</b>, <b>Jungbunny</b>, <b>Ashish</b> or others.</li>
                <li>New Players: <b>New players</b> must choose which team to join upon entering the server.</li>
            </ul>

            <h3>5. Stealing and PvP:</h3>
            <ul>
                <li>You are allowed to <b>steal items</b> from the <b>opponent's base</b>, but only if you're not caught in the act.
                </li>
                <li>You can <b>kill</b> members of the opposing team to loot their items, but only if they are <b>outside</b> their
                    base.</li>
            </ul>

            <h3>6. Base Entry Rules:</h3>
            <ul>
                <li>You cannot <b>enter</b> the opponent's base if any of their <b>team members</b> are inside.</li>
            </ul>
        </div> -->


        <br>
        <br>
        <h2>How to join the self hosted minecraft server</h2>
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
* {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    line-height: 1.6em;
    box-sizing: border-box;
    color: rgb(70, 70, 70);
}

body{
    background-color: blanchedalmond !important;
}

.note {
    background-color: rgba(255, 208, 0, 0.596);
    padding: 0 1em;
}

ul {
    list-style-type: disc;
    margin-left: 2em;

}

b{
    font-weight: 500;
    /* background-color: rgba(0, 0, 0, 0.144); */
}

.rules b{
    padding: 0.2em 0.5em;
    border: 1px solid rgb(224, 224, 224);
    border-radius: 4px;
    background-color: white !important;
    white-space: nowrap;
}

ul li{
    margin: 1em 0;
    line-height: 1.8em;
}

.rules h3{
    margin-top: 2em;
}

h1,
h2,
h3,
p {
    margin: 1em 0;
}

h1 {
    font-size: 42px;
}

h2 {
    font-size: 32px;
}

.page {
    max-width: 1000px;
    padding: 1rem;
    margin: auto;
}

.page img {
    width: 100%;
    display: block;
    margin-top: 3rem;
}
</style>