<template>
    <div>
        <!-- Company Area -->
        <Company />
        <!-- End Company Area -->

        <!-- Services Area -->
        <Services />
        <!-- End Services Area -->

        <!-- Process Area -->
        <Process />
        <!-- End Process Area -->

        <!-- Team Area -->
        <Team />
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
import Process from './Process.vue';
import Team from './Team.vue'

    export default {
        name: 'Main',
        components: {
            Company,
            Services,
            Process,
            Team,
        }
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

</style>