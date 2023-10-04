<script>
import sectionOne from './sectionOne.vue';
import sectionTwo from './sectionTwo.vue';
import sectionThree from './sectionThree.vue';

export default{
    name: 'appMain',

    components:{
        sectionOne,
        sectionTwo,
        sectionThree
    }
}
</script>

<template>

<sectionOne></sectionOne>

<sectionTwo></sectionTwo>

<sectionThree></sectionThree>

</template>