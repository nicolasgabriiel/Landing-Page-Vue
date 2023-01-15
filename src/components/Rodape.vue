<template>
    <footer>
        <div class="logomarca"> <img src="../assets/logo.svg" alt=""></div>
        <div class="informacoes">
            <div class="texto-do-local">
                <div class="iconelocal"><img src="../assets/icon-location.svg" alt=""></div>
                <div class="texto">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</div>
            </div>
            <div class="contato">
                <p><img src="../assets/icon-phone.svg" alt="">+1-543-123-4567</p>
                <p><img src="../assets/icon-email.svg" alt="">example@fylo.com</p>
            </div>
            <div class="casulo">
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
    padding: 300px 150px 200px 150px;
    font-family: 'Open Sans';
}
.logomarca{
    margin-bottom: 50px;
}
.informacoes{
    display:flex;
    justify-content: space-between;
}
.texto{
    margin-left: 15px ; 
    color: white;
    width:300px;
    line-height: 25px;
}
.contato img{
    margin-right: 15px;
    display: inline-block;
}
.contato p:last-child{
    margin-top: 20px;
}
.contato p{

    color:white;

}
img{
    display: block;
}
.dados li{ 
    color: white;
    padding-bottom: 20px;
}
.dados li:hover{
    cursor: pointer;
    text-decoration: underline;
    font-weight: bold;
}
.dados{
    margin-right: 50px;
}
.redes img{
    margin-right: 20px;
    display: inline-block;
    width: 30px;
    transition: .5s;
}
.redes img:hover{
    scale: 1.05;
    cursor: pointer;
}
.casulo, .texto-do-local{
    display: flex;
}

</style>