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
                <i class="fa-regular fa-copyright"></i>
                Copyright 2012-2020|Avada Theme by <span>ThemeFusion</span>|All Rights Reserved|Powered by <span>WordPress</span>
            </p>   
            </div>
            
        </div>

        <div class="arrow">
            <i class="fa-solid fa-chevron-up"></i>
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
    height: 550px;
    background-color: #0d1167;
    color: white;
    position: relative;

    background-image: url(../assets/_img/footer-bg-1.svg);
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover;
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

        &:hover {
            background-color: #f86635;
            color: white;
        }
    }

span{
    color: #f86635;
}

.arrow{
    width: 40px;
    height: 25px;
    background-color: #2f3038;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    text-align: center;
    vertical-align: middle;
    position: absolute;
    bottom: 0px;
    left: 100px;

    &:hover{
        background-color: white;
        color: #2f3038;
    }
}
.alert{
    width: 150px;
    height: 120px;
    background-color: white;
    border-radius: 3px;
    position: absolute;
    right: 20px;
    bottom: 70px;
    box-shadow:  1px 1px 5px lightgray;
    

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

    &:hover{
        background-color: white;
        color: #f86635;
        border: #f86635 1px solid;
    }
}
</style>