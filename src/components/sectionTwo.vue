<script>

export default {
    name: 'sectionTwo'
}
</script>

<template>
    <div class="sectionTwo">

        <div class="row top text-center">
            <p>
                Lorem ipsum dolor sit amet consectetur.
            </p>
            <h3 class="slogan">
                Highly-skilled, independent <br> professional freelacers.
            </h3>
            <div>
                <a href="#">
                    What is a VA exactly?
                </a>
            </div>

        </div>

        <div class="container">
            <div class="row bottom ">

                <div class="col-4">
                    <div class="card mb-3">
                        <div class="row">
                            <div class="col-md-3">
                                <h3 class="text-center">1.</h3>
                            </div>
                            <div class="col-md-9">
                                <div class="card-body">
                                    <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                                        Voluptates iusto minus sapiente earum non blanditiis.</p>
                                    <p>
                                        <a href="#">Learn more</a>
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-4">
                    <div class="card mb-3">
                        <div class="row">
                            <div class="col-md-3">
                                <h3 class="text-center">2.</h3>
                            </div>
                            <div class="col-md-9">
                                <div class="card-body">
                                    <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                                        Voluptates iusto minus sapiente earum non blanditiis.</p>
                                    <p>
                                        <a href="#">Learn more</a>
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card mb-3">
                        <div class="row">
                            <div class="col-md-3">
                                <h3 class="text-center">3.</h3>
                            </div>
                            <div class="col-md-9">
                                <div class="card-body">
                                    <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                                        Voluptates iusto minus sapiente earum non blanditiis.</p>
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
</template>


<!-- SCSS -->
<style lang="scss" scoped>
.sectionTwo {
    width: 100%;
    min-height: 800px;
    background-color: #0d1167;
    color: white;

    background-image: url(../assets/_img/info-bg-3.svg);
    background-position: bottom;
    background-repeat: no-repeat;
}

.top {
    padding-top: 100px;

    a {
        text-decoration: none;
        color: white;
        background-color: #f86635;
        padding: 10px 30px;
        border-radius: 2px;
        font-size: 15px;

        &:hover {
            background-color: white;
            color: #0d1167;
        }
    }
}

.slogan{
    font-size: 50px;
}

h3 {
    font-size: 40px;
    padding: 20px 0px 50px 0px;   
}

.col-4 {
    padding: 30px;
}

.card {
    background-color: #000545;
    min-height: 100px;
    color: white;
    border-radius: 0px;

    .row {
        padding: 20px;
    }

    a {
        text-decoration: none;
        color: #f86635;

        &:hover {
            text-decoration: underline;
        }
    }
}

.bottom {
    margin-top: 100px;
}
</style>