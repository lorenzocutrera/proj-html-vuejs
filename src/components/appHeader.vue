<script>
import appNavbar from './appNavbar.vue';

export default {
    name: 'appHeader',

    components: {
        appNavbar
    }
}

</script>

<template>
    <div class="jumbotron">

        <appNavbar></appNavbar>

        <div class="container d-flex">
            <div class="row d-flex">
                <div class="sx col-6 text-center">
                    <h3>Independent professional who works remotely to help with your business.
                    </h3>

                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. nesciunt laudantium
                        est sequi non voluptate. Voluptatem, porro?
                    </p>

                    <a href="#">
                        What is a VA exactly?
                    </a>
                </div>
                <div class="col-6">
                    <div class="img_5">
                        <img width="100%" src="../assets/_img/info-5.jpg" alt="">
                    </div>

                </div>
            </div>

        </div>

        <div class="badges">
            <div class="badge_on"></div>
            <div class="badge_on"></div>
        </div>

    </div>
</template>


<style lang="scss" scoped>
.jumbotron {
    width: 100%;
    min-height: 600px;
    background-color: #0d1167;
    color: white;
}

.row {
    align-items: center;
}


h3 {
    font-size: 50px;
    padding: 50px 0px;
}

p {
    padding-bottom: 30px;
}

a {
    text-decoration: none;
    background-color: white;
    color: #0d1167;
    padding: 10px 30px;
    border-radius: 2px;
    font-size: 15px;
}

.img_5 {
    width: 100%;
    height: 100%;
    padding: 0px 50px;
}

.badges{
    min-width: 50px;
    min-height: 100px;
    position: absolute;
    right: 10px;
    top: 100px;
    
}
.badge_on{
    width: 60px;
    aspect-ratio: 1 / 1;
    background-color: white;
    border-radius: 2px;
    margin-bottom: 5px;

}
</style>