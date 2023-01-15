<template>
    <form class="container">
        <div class="box">
            <h5>Get early access today</h5>
            <p>It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.</p>
            <div class="form">
                <input type="email" placeholder="email@example.com"/>
                <button>Get Started For Free</button>
            </div>
        </div>
    </form>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent ({
    name: 'Acesso-Antecipado'
})
</script>

<style scoped>
.container{
    background-color: #181F2B;
    display: flex;
    align-items: center;
    justify-content: center;
}
.box{
    position: relative;
    top: 150px;
    width: 40%;
    text-align: center;
    background-color: #21293C;
    padding: 50px 100px;    
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    box-shadow: 10px 10px 5px 0px #141724;
    border-radius:5px; 
}
.box h5{
        font-family: 'Open Sans';
        color: white;
        font-weight: bold;
        font-size: 40px;
        margin-bottom: 25px;
}
.box p{
    color: white;
    font-family: 'Open Sans';
    font-size: 15px;
    width: 80%;
    line-height: 20px;
    margin-bottom: 50px;
}
.form{
    width: 100%;
    display: flex;
    justify-content: space-between;
}
.form input{
    width: 60%;
    font-family: 'Open Sans';
    font-size: 15px;
    padding: 15px 30px;
    border-radius: 30px;
    border: 0;
}
.form input:invalid{
    border: 3px solid #8d1111;
}
.form button{
    font: 'Raleway';
    font-size: 15px;
    color: white;
    font-weight: bold;
    background-color: #4EC3D4;
    transition: .7s;
    border: none;
    border-radius: 30px;
    padding: 0 30px;
}
.form button:hover{
    background-color: #5eb9c7;
    scale: 1.05;
    cursor: pointer;
}

</style>