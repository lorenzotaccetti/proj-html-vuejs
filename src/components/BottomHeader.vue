<template>
    <div class="bottom-header">
        <div class="container disposition">
            <div class="text-logo">
                <span class="nex_title">
                    n e x
                </span>
                <span>
                    g e n
                </span>
            </div>
            <div class="menu-nav">
                <div 
                class="menu-element" 
                v-for="element in navArray" 
                :key="element.id"
                :class="{'m_button' : element.status}">
                    {{element.navElement}}
                </div>
            </div>
        </div>
        <div class="container">
            <Jumbotron />
        </div>
    </div>
</template>

<script>
import Jumbotron from './Jumbotron.vue'
    export default {
        name: 'BottomHeader',
        components: {
            Jumbotron
        },
        props:{
            navArray: Array
        }
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.bottom-header{
    text-transform: uppercase;
    font-size: 20px;
    padding: 25px 0;
    color: $mainFontColor;
    background-image: url(../assets/img/bg-6.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    .disposition{
        display: flex;
        align-items: center;

        .text-logo{
            flex-grow: 1;
            font-weight: 600;

            .nex_title{
                border-color: #aedbde;
                background-color: #aedbde;
                color: $buttonIconColor;
                margin-right: 5px;
            }
        }

        .menu-nav{
            display: flex;
            align-items: center;

            .menu-element{
                margin-left: 35px;
                color: $secondaryFontColor;
                cursor: pointer;

                &:hover{
                    text-decoration: underline;
                }
            }

            .m_button{
                background-color: $buttonIconColor;
                color: white;
            }
        }
    }
}
</style>