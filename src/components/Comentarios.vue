<template>
    <div class="container">
        
        <div class="box">
                <div class="comentarios">
                    <div class="cima">
                        <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-olled collaboration machine.</p>
                    </div><!--cima-->
                    <div class="baixo">
                        
                        <div class="imagem imagem1">
                        </div>
                        <div class="titulos">
                            <span>Satish Patel</span>
                            <span>Founder & CEO, Huddle</span>
                        </div><!--titulos-->
                    
                    </div><!--baixo-->
                </div><!--comentarios-->
                <div class="comentarios">
                    <div class="cima">
                        <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-olled collaboration machine.</p>
                    </div><!--cima-->
                    <div class="baixo">
                        
                        <div class="imagem imagem2">       
                        </div>
                        <div class="titulos">
                            <span>Bruce McKenzie</span>
                            <span>Founder & CEO, Huddle</span>
                        </div><!--titulos-->
                    
                    </div><!--baixo-->
                </div><!--comentarios-->
                <div class="comentarios">
                    <div class="cima">
                        <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-olled collaboration machine.</p>
                    </div><!--cima-->
                    <div class="baixo">
                        
                        <div class="imagem imagem3">
                        </div>
                        <div class="titulos">
                            <span>Iva Boyd</span>
                            <span>Founder & CEO, Huddle</span>
                        </div><!--titulos-->
                    
                    </div><!--baixo-->
                </div><!--comentarios-->
        </div><!--box-->

    </div>
</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent({
    name: 'Comentarios-landing-page',
})
</script>

<style scoped>
    .container{
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #181F2B;
    }
    .box{
        width: 70%;
        background-image: url(../assets/bg-quotes.png);
        background-repeat: no-repeat ;
        display: flex;
    }
    .comentarios{
        margin: 40px 20px 40px 10px;
        background: #21293C;
        box-shadow: 10px 10px 5px 0px #141724;
        border-radius: 5px;
    }
    .cima p{
        padding: 40px 30px 25px 30px;
        color: white;
        font-family: 'Open Sans';
        font-size: 17px;
        line-height: 20px;
    }
    .baixo{
        display: flex;
        padding-bottom: 30px ;
    }
    .titulos{
        display:flex;
        flex-direction: column;
        align-items: right;
        margin-left: 10px;
        font-family: 'Open Sans';
        color: white;
    }
    .titulos span:first-child{
        font-size: 14px;
        font-weight: bold;
    }
    .titulos span:last-child{
        font-size: 10px;
        margin-top: 3px;
    }
    .imagem{
        width: 30px;
        height: 30px;
        border-radius: 15px;
        background-size: cover;
        margin-left: 30px;
    }
    .imagem1{background-image: url(../assets/profile-1.jpg);}
    .imagem2{background-image: url(../assets/profile-2.jpg);}
    .imagem3{background-image: url(../assets/profile-3.jpg);}

</style>