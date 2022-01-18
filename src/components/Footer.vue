<template>
    <div>
        <!-- Top Footer -->
        <TopFooter :about="about" :services="services" :support="support" />
        <!-- End Top Footer -->

        <!-- Bottom Footer -->
        <BottomFooter />
        <!-- End Bottom Footer -->
    </div>
</template>

<script>
import TopFooter from './TopFooter.vue';
import BottomFooter from './BottomFooter.vue';

    export default {
        name: 'Footer',
        components: {
            TopFooter,
            BottomFooter
        },
        data: function() {
            return {
                about:[
                    'The Company', 'Institutional', 'Social & Events', 'Innovation', 'Environment', 'Technology'
                ],
                services: [
                    'Audit & Assurance', 'Financial Advisory', 'Analytics M&A','Middle Marketing', 'Legal Consulting', 'Regulatory Risk'
                ],
                support: [
                    'Responsability', 'Terms of Use', 'About Cookies', 'Privacy Policy', 'Accessibility', 'Information'
                ]
            }
        },
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

</style>