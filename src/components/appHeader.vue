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
            <div class="badge_on">
                <div class="icon">
                    <i class="fa-brands fa-atlassian"></i>
                </div>
                <p class="text-center demos">Demos</p>
            </div>

            <div class="badge_on">
                <h2 class="text-center">
                    <i class="fa-solid fa-dollar-sign"></i>
                    39
                </h2>
                <p class="text-center sale">On Sale</p>
            </div>
        </div>

    </div>
</template>



<!-- SCSS -->
<style lang="scss" scoped>
.jumbotron {
    width: 100%;
    min-height: 600px;
    background-color: #0d1167;
    color: white;
    

    background-image: url(../assets/_img/home-bg-3.svg);
    background-size: cover;
    background-position: bottom;
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

    &:hover {
        background-color: #f86635;
        color: white;
    }
}

.img_5 {
    width: 100%;
    height: 100%;
    padding: 0px 50px;
}

.badges {
    min-width: 50px;
    min-height: 100px;
    position: absolute;
    right: 10px;
    top: 100px;

}

.badge_on {
    width: 60px;
    aspect-ratio: 1 / 1;
    background-color: white;
    border-radius: 2px;
    margin-bottom: 5px;

    h2 {
        color: #65bc7c;
        padding: 0px;
        margin: 0px;
        font-size: 28px;
        position: relative;

        i {
            font-size: 15px;
            position: absolute;
            left: 4px;
            top: 4px;
        }
    }

    .sale {
        color: grey;
        padding: 0px;
        font-size: 12px;
    }


}

.icon {
    background-color: gray;
    width: 30px;
    height: 30px;
    position: absolute;
    right: 15px;
    top: 15px;
}

.demos {
    color: gray;
    font-size: 12px;
    padding-bottom: 0px;
    position: absolute;
    top: 43px;
    left: 10px;
}
</style>