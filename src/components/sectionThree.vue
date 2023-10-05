<script>
export default {
    name: 'sectionThree'
}

</script>

<template>
    <div class="sectionThree">
        <div class="container">

            <div class="top text-center">
                <h5>Trusted by these amazing brands</h5>
                <div class="row">
                    <div class="brand">
                        <a href="#">
                            <img src="../assets/_img/brand-1-200x67.jpg" alt="">
                        </a>
                    </div>
                    <div class="brand">
                        <a href="#">
                            <img src="../assets/_img/brand-7-200x67.jpg" alt="">
                        </a>
                    </div>
                    <div class="brand">
                        <a href="#">
                            <img src="../assets/_img/brand-3-200x67.jpg" alt="">
                        </a>
                    </div>
                    <div class="brand">
                        <a href="#">
                            <img src="../assets/_img/brand-4-200x67.jpg" alt="">
                        </a>
                    </div>
                    <div class="brand">
                        <a href="#">
                            <img src="../assets/_img/brand-5-200x67.jpg" alt="">
                        </a>
                    </div>
                </div>
            </div>

            <div class="middle">
                <div class="row d-flex">
                    <div class="sx col-6 text-center d-flex">
                        <div class="icon">
                            <img width="200px" src="../assets/_img/icon-2-2x.png" alt="">
                        </div>

                        <h3>
                            Professional who works to help with your business.
                        </h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolore, nisi?
                        </p>
                        <div class="button">
                            <a href="#">
                                What is a VA exactly?
                            </a>
                        </div>

                    </div>
                    <div class="dx col-6">
                        <img width="100%" src="../assets/_img/info-8-2x.png" alt="">
                    </div>
                </div>
            </div>

            <div class="bottom">
                <div class="row">
                    <div class="col-6">
                        <div class="card mb-3">
                            <div class="corner"></div>
                            <div class="row">
                                <div class="col-md-2">
                                    <h3 class="text-center">1.</h3>
                                </div>
                                <div class="col-md-10">
                                    <div class="card-body">
                                        <h5>
                                            Learn to delegate
                                        </h5>
                                        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore
                                            exercitationem voluptates delectus! Incidunt quo libero ab minus, laudantium
                                            quod nisi?</p>
                                        <p>
                                            <a href="#">Learn more</a>
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="card mb-3">
                            <div class="row">
                                <div class="col-md-2">
                                    <h3 class="text-center">2.</h3>
                                </div>
                                <div class="col-md-10">
                                    <div class="card-body">
                                        <h5>
                                            Reduce labor costs
                                        </h5>
                                        <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                                            Dignissimos earum doloribus aliquid delectus quos excepturi cumque eveniet autem
                                            odit sapiente.</p>
                                        <p>
                                            <a href="#">Learn more</a>
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>

    </div>
</template>


<!-- SCSS -->
<style lang="scss" scoped>
.sectionThree {
    width: 100%;
    min-height: 1000px;
}

.top {
    margin: 100px 0px;

    h5 {
        color: #f86635;
    }
}

.brand {
    width: calc(100% / 5);

    img {
        width: 100%;
    }

    :hover {
           border-bottom: #0d1167 solid 1px;
        }
}

.dx {
    padding: 30px;
}

.sx {
    flex-direction: column;
    color: #0d1167;

    h3 {
        font-size: 40px;
        padding: 40px;
    }

    p {
        padding: 0px 100px;
    }

    a {
        text-decoration: none;
        color: white;
        background-color: #f86635;
        padding: 10px 30px;
        border-radius: 2px;
        font-size: 15px;

        &:hover {
            background-color: #0d1167;
        }
    }
}

.icon {
    margin-top: 60px;
    padding: 30px;
}

.button {
    padding-top: 20px;
}

.card {
    background-color: #0d1167;
    min-height: 100px;
    color: white;
    border-radius: 0px;
    position: relative;

    h3 {
        font-size: 40px;
    }

    .row {
        padding: 30px;
        padding-top: 50px;
    }


    a {
        text-decoration: none;
        color: #f86635;

        &:hover {
            text-decoration: underline;
        }
    }

    
}

.corner{
        width: 100px;
        height: 100px;
        background-color: #f86635;
        border-top-right-radius: 100%;
        position: absolute;
        bottom: 0px;
    }
</style>