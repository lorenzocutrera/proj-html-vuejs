<script>

export default {
    name: 'sectionOne'
}
</script>

<template>
    <div class="sectionOne">
        <section class="top">
            <div class="container">

                <h5>Available services</h5>

                <div class="row d-flex">
                    <div class="col-3">
                        <h3>Aswering phone calls</h3>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vitae, iusto.
                        </p>
                    </div>
                    <div class="col-3">
                        <h3>Basic data entry</h3>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis, distinctio?
                        </p>
                    </div>
                    <div class="col-3">
                        <h3>Organizing calendar</h3>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure, ex!
                        </p>
                    </div>
                    <div class="col-3 travel">
                        <h3>Booking travels</h3>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, deserunt.
                        </p>
                    </div>
                </div>
            </div>
        </section>



        <section class="bottom">

            <div class="container">
                <div class="row d-flex">
                    <div class="sx col-6">
                        <img width="100%" src="../assets/_img/info-5-2x.png" alt="">
                    </div>

                    <div class="dx col-6 text-center d-flex">
                        <div class="icon">
                            <img width="200px" src="../assets/_img/icon-1-2x.png" alt="">
                        </div>

                        <h3>
                            Find the ultimate virtual assistant for your business
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
                </div>

            </div>
        </section>
    </div>
</template>

<style lang="scss" scoped>
.sectionOne {
    width: 100%;
    min-height: 1000px;
    color: #0d1167;
}

.top {
    padding-top: 50px;
}

h5 {
    color: #f86635;
    padding: 20px 0px;
}

.col-3 {
    padding: 70px;
    border-top: solid #f0f1f5;
    border-right: solid #f0f1f5;

    :hover {
        text-decoration: underline;
    }
}

.travel {
    border-right: none;
}

.sx {
    padding: 30px;
}

.dx {
    flex-direction: column;

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
    }
}

.icon {
    margin-top: 60px;
    padding: 30px;
}

.button{
    padding-top: 20px;
}
</style>