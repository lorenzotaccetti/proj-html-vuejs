<template>
    <div class="bottom-footer">
        <div class="container">
            <div class="d-flex justify-content-between">
                <div class="footer-text">
                    Enjoy the low price. We are tracking any intention of piracy.
                </div>
                <div class="footer-text">
                    <i class="far fa-copyright"></i>
                    2020 NEXGEN is Proudly Powered by <span class="color">Codings</span>.
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'BottomFooter'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.bottom-footer{
    background-color: black;
    padding: 30px 0;

    .footer-text{
        color: $lightFontColor;
        font-size: $textFontSize;

        .color{
            color: $buttonIconColor;
            cursor: pointer;

            &:hover{
                text-decoration: underline;
            }
        }
    }
}
</style>