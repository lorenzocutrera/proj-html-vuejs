<script>

export default {
    name: 'appNavbar'
}

</script>

<template>
    <nav class="d-flex">

        <div class="sx col-6 d-flex">
            <div class="logo">
                <img width="50px" src="../assets/_img/logo-2x.png" alt="">
            </div>

            <div class="pages d-flex">

                <div class="page">
                    <a href="#">Home</a>
                </div>

                <div class="page">
                    <a href="#">About</a>
                </div>

                <div class="page">
                    <a href="#">Service</a>
                </div>

                <div class="page">
                    <a href="#">Journal</a>
                </div>

                <div class="page">
                    <a href="#">Contact</a>
                </div>

            </div>
        </div>


        <div class="dx col-6 d-flex">
            <div class="get d-flex">
                <div class="call">
                   1.800.123.4567
                </div>
                <a href="#">
                    Get a free consultation
                </a>
            </div>
        </div>

    </nav>
</template>

<style lang="scss" scoped>
nav {
    width: 100%;
    height: 100px;
    align-items: center;
}

.row {
    justify-content: space-between;
}

.sx {
    align-items: center;
}

.page {
    padding: 20px;

    a {
        text-decoration: none;
        color: white;
        border-bottom: white;
        padding: 10px 0px;
    }

    :hover {
        border-bottom: solid 1px white;
    }
}

.logo {
    width: 50px;
    aspect-ratio: 1 / 1;
    margin: 0 50px;
}

.dx {
    justify-content: flex-end;
}

.get{
    margin: 0px 50px;
    align-items: center;
    color: white;

    .call{
        margin: 0px 50px;
        padding: 10px 0px;


        &:hover{
            border-bottom: solid 1px white;
        }
    }

    a{
        text-decoration: none;
        background-color: white;
        padding: 10px 30px;
        border-radius: 2px;
        color: #0d1167;
        font-size: 15px;

    }
}
</style>