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

            <h3>
                Independent professional who works remotely to help with your business.
            </h3>

            <a href="#">
                What is a VA exactly?
            </a>

            <p>
                Copyright 2012-2020|Avada Theme by <span>ThemeFusion</span>|All Rights Reserved|Powered by <span>WordPress</span>
            </p>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
footer {
    width: 100%;
    height: 400px;
    background-color: #0d1167;
    color: white;
}


span{
    color: #f86635;
}
</style>