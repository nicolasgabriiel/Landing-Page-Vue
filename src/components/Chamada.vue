<template>
    <div>
        <img src="../assets/illustration-intro.png" alt="Imagem de chamada pra ação">
        <h2>
            All your files in one secure location, <br/> accessible anywhere.
        </h2>
        <p>Fylo Stores all your most importante files in one secure location. Access them wherever you need, share and collaborate with firends family, and co-workers.</p>
        <button>Get Started</button>
    </div>
</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent ({
    name: 'chamadaPraAcao',
})
</script>

<style scoped>

div{
    display: flex;
    flex-direction: column;
    align-items: center;
    background-image: url(../assets/bg-curvy-desktop.svg);
    background-repeat: no-repeat;
    background-size: contain;
    background-position: bottom;
    padding-bottom: 250px;
}
h2, p{
    color: white;
}
h2{
    font-size: 40px;
    font-weight: bold;
    text-align: center;
    margin: 30px 0 20px;
    line-height: 45px;
}
p{
    font-size: 22px;
    width: 650px;
    text-align: center;
    letter-spacing: 1px;
    margin: 10px 0 50px;
    line-height: 30px;
}
button{
    color: white;
    font-size: 17px;
    font-weight: bold;
    border-radius: 40px;
    transition: .7s;
    background-color: #4EC3D4;
    padding: 20px 100px;
}
button:hover{
    background-color: #5eb9c7;
    scale: 1.05;
    cursor: pointer;
}
</style>