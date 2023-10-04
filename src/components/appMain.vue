<script>
import sectionOne from './sectionOne.vue';
import sectionTwo from './sectionTwo.vue';

export default{
    name: 'appMain',

    components:{
        sectionOne,
        sectionTwo
    }
}
</script>

<template>

<sectionOne></sectionOne>

<sectionTwo></sectionTwo>

<sectionThree></sectionThree>

</template>