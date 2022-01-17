<template>
    <div>
            <!-- Top Header -->
            <TopHeader />
            <!-- End Top Header -->

            <!-- Bottom Header -->
            <BottomHeader :navArray="navArray" />
            <!-- End Bottom Header -->
    </div>
</template>

<script>
import TopHeader from './TopHeader.vue';
import BottomHeader from './BottomHeader.vue'
    export default {
        name: 'Header',
        components: {
            TopHeader,
            BottomHeader
        },
        data:function(){
            return{
                navArray: [
                    {
                        id: 1,
                        navElement: 'home',
                        status: false
                    },
                    {
                        id: 2,
                        navElement: 'about',
                        status: false
                    },
                    {
                        id: 3,
                        navElement: 'services',
                        status: false
                    },
                    {
                        id: 4,
                        navElement: 'process',
                        status: false
                    },
                    {
                        id: 5,
                        navElement: 'team',
                        status: false
                    },
                    {
                        id: 6,
                        navElement: 'blog',
                        status: false
                    },
                    {
                        id: 7,
                        navElement: 'get in touch',
                        status: true
                    }
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

</style>