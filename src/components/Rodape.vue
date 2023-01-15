<template>
    <footer>
        <div class="logomarca"></div>
        <div>
            <div class="iconelocal"><img src="../assets/icon-location.svg" alt=""></div>
            <div class="texto">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</div>
            <div class="contato">
                <p><img src="../assets/icon-phone.svg" alt="">+1-543-123-4567</p>
                <p><img src="../assets/icon-email.svg" alt="">example@fylo.com</p>
            </div>
            <div class="dados">
                <ul>
                    <li>About Us</li>
                    <li>Jobs</li>
                    <li>Press</li>
                    <li>Blog</li>
                </ul>
            </div>
            <div class="dados">
                <ul>
                    <li>Contact Us</li>
                    <li>Terms</li>
                    <li>Privacy</li>
                </ul>
            </div>
            <div class="redes">
                <img src="../assets/facebook.png"/>
                <img src="../assets/twitter.png"/>
                <img src="../assets/instagram.png"/>
            </div>
        </div>
    </footer>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name:'Rodape-LP',
})
</script>

<style scoped >
footer{
    background-color: #0C1524;
}
</style>