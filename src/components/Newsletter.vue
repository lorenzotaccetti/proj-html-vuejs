<template>
    <div class="newsletter-area">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-6">
                    <div class="intestazione">
                        Newsletter
                    </div>
                    <div class="main-area-title">
                        <span class="main-area-title-detail-dark">Know</span>
                        First
                    </div>
                    <div class="newsletter-text">
                        Follow closely and receive content about our company and the news of the current market.
                    </div>
                </div>
                <div class="col-6">
                    <div>
                        <input type="text" placeholder="Name">
                    </div>
                    <div>
                        <input type="text" placeholder="Email" name="" id="">
                    </div>
                    <div class="m_button">
                        Subscribe
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Newsletter'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.newsletter-area{
    background-image: url(../assets/img/bg-1.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    padding: 125px 0;

    .main-area-title{
        color: white;
    }

    .newsletter-text{
        font-size: $textFontSize;
        color: $lightFontColor;
    }

    input{
        border: none;
        margin-bottom: 20px;
        width: 400px;
        padding: 10px;
        border-radius: 7px;
        color: $lightFontColor;
        background-color: rgba(255 , 255, 255, 0.4);
    }

    .m_button{
        background-color: $buttonIconColor;
        display: inline-block;
    }
}
</style>