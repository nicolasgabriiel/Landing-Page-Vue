<template>
    <div class="container">
        <div class="encapsular">
            
            <div>
                <img src="../assets/illustration-stay-productive.png" alt="">
            </div>
            <div class="textos">
                <h4>Stay productive, wherever you are</h4>
                <p>Never let location be an issue when acessing your files. Fylo has you covered for all of your file storage needs.</p>
                <p>Securely share files and folders with frieds, family and colleagues for live collaboration. No email attachments required.</p>
                <button>
                    <span>See how fylo works</span>
                    <img src="../assets/icon-arrow.svg" alt="">
                </button>

            </div>           
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'Segunda-Chamada',
})
</script>

<style scoped>
    .container{
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #181F2B;
    }
    .encapsular{
        display: flex;
        align-items: center;
        justify-content: center;
    }   
    .textos{
        width: 40%;
        margin-left: 50px;
    }
    .textos h4{
        line-height: 50px;
        width: 70%;
        font-family: 'Open Sans';
        color: white;
        font-weight: bold;
        font-size: 40px;
    }
    .textos p {
        font-family: 'Open Sans';
        color: white;
        margin-top: 20px;
        font-size: 16px;
        line-height: 20px;
    }
    button{
        margin-top: 30px;
        background-color: transparent;
        border: none;
        padding: 0 0 2px 0;
        border-bottom: 1px solid #62E0D9;
        transition: .5s ; 
    }
    button:hover{
        cursor: pointer; 
        scale: 1.03;
    }
    button span{
        font-size: 16px;
        color: #62E0D9;
        font-family: 'Raleway';
        margin-right: 5px;
    }
    button img{
        position: relative;
        top: 3px;
    }

</style>