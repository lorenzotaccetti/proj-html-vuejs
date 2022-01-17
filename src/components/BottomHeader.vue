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
    </div>
</template>

<script>
    export default {
        name: 'BottomHeader',
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

    .disposition{
        display: flex;
        align-items: center;

        .text-logo{
            flex-grow: 1;
            font-weight: 600;

            .nex_title{
                border-color: #bbf2f5;
                background-color: #bbf2f5;
                color: $decorationColor;
                margin-right: 3px;
            }
        }

        .menu-nav{
            display: flex;
            align-items: center;

            .menu-element{
                margin-left: 35px;
                color: $secondaryFontColor;
            }

            .m_button{
                background-color: $buttonIconColor;
                color: white;
            }
        }
    }
}
</style>