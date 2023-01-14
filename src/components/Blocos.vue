<template>
    <div class="container">
        
        <div class="encapsular">
            
            <div class="blocos"> 
                <img src="../assets/icon-access-anywhere.svg"/> 
                <h3>Access yout files, anywhere</h3> 
                <p>The ability to use a smartphone, tablet, or computer to acess your accoount means yout files follow you everywhere.</p> 
            </div>
            
            <div class="blocos"> 
                <img src="../assets/icon-security.svg"/>  
                <h3>Security you can trust</h3> 
                <p>2-factor authentication and user-controlled encryption are just a couple of the features we allow to help secure your files.</p> 
         
            </div>

        </div><!-- encapsular -->
        
        <div class="encapsular">
        
            <div class="blocos"> 
                <img src="../assets/icon-collaboration.svg"/> 
                <h3>Real-time collaboration</h3> 
                <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p> 
            </div>
            
            <div class="blocos"> 
                <img src="../assets/icon-any-file.svg"/> 
                <h3>Store any type of file</h3> 
                <p>Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.</p> 
             </div> 
        
        </div><!--encapsular-->
        
      
    </div><!-- container -->

</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent ({
    name: 'Bloco-4'
})


</script>

<style scoped>
.container{
    background-color: #181F2B;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.encapsular{
    width: 50%;
    display: flex;
    justify-content: space-between;
}
.blocos{
    width: 38%;
    text-align: center;
}
.blocos h3{
    color: white;
    font-size: 21px;
    font-weight: bold;
    padding: 20px 0 10px 0;
}
.blocos p{
    color: white;
    margin-bottom: 100px;
}
</style>
