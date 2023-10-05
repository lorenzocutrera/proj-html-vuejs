<script>
import appNavbar from './appNavbar.vue';

export default {
    name: 'appFooter',

    components: {
        appNavbar
    }
}
</script>

<template>
    <footer>
        <div class="container">
            <appNavbar></appNavbar>
            <div class="sx">
             <h3>
                Independent professional who works <br> remotely to help with your business.
            </h3>

            <a href="#">
                What is a VA exactly?
            </a>

            <p>
                Copyright 2012-2020|Avada Theme by <span>ThemeFusion</span>|All Rights Reserved|Powered by <span>WordPress</span>
            </p>   
            </div>
            
        </div>

        <div class="alert">
            <div class="logo">
                <img src="../assets/_img/logo-2x.png">
            </div>
            
            <p>
                This is a free HubSpot live chat. You can create your own chat flows and engage your customer with Avada & HubSpot!  
            </p>
        </div>

        <div class="icon d-flex">
            <i class="fa-solid fa-comment"></i>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    width: 100%;
    height: 400px;
    background-color: #0d1167;
    color: white;
    position: relative;
}

h3{
    font-size: 30px;
    padding: 30px 0px;
}

.sx p{
    padding: 40px 0px;
}

a {
        text-decoration: none;
        color: #0d1167;
        background-color: white;
        padding: 10px 30px;
        border-radius: 2px;
        font-size: 15px;
    }

span{
    color: #f86635;
}

.alert{
    width: 150px;
    height: 120px;
    background-color: white;
    border-radius: 3px;
    position: absolute;
    right: 20px;
    bottom: 70px;
    

    .logo{
        width: 30px;
        aspect-ratio: 1 / 1;
        position: absolute;
        top: -15px;
        left: 60px;

        img{
            width: 100%;
        }
    }

    p{
        color: #5b6c7c;
        font-size: 10px;
    }
}

.icon{
    width: 50px;
    aspect-ratio: 1 / 1;
    border-radius: 50%;
    background-color: #f86635;
    position: absolute;
    right: 20px;
    bottom: 20px;
    justify-content: center;
    align-items: center; 
}
</style>