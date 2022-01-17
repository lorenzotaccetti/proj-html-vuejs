<template>
    <div>
        <!-- Company Area -->
        <Company />
        <!-- End Company Area -->

        <!-- Services Area -->
        <Services />
        <!-- End Services Area -->

        <!-- Process Area -->
        <!-- End Process Area -->

        <!-- Team Area -->
        <!-- End Team Area -->

        <!-- News Area -->
        <!-- End News Area -->

        <!-- Newsletter Area -->
        <!-- End Newsletter Area -->
    </div>
</template>

<script>
import Company from './Company.vue';
import Services from './Services.vue';

    export default {
        name: 'Main',
        components: {
            Company,
            Services
        }
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

</style>