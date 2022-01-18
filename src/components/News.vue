<template>
    <div class="news-area">
        <div class="container">
            <div class="intestazione">
                Our editorial content
            </div>
            <div class="main-area-title">
                Latest
                <span class="main-area-title-detail-light">News</span>
            </div>
            <div class="d-flex justify-content-between mb-5">
                <div class="">
                    <div class="news-text">
                        Every week we publish content about what is best in the business world.
                    </div>
                </div>
                <div class="">
                    <a class="m_button">
                        See All
                    </a>
                </div>
            </div>
            <div class="row">
                <div class="col-4">
                    <div class="news-box">
                        <img src="../assets/img/news-1.jpg" alt="">
                        <div class="overlay"></div>
                        <span class="news-titolini">Increasing creativity is possible for everyone</span>
                    </div>
                </div>
                <div class="col-4">
                    <div class="news-box">
                        <img src="../assets/img/news-2.jpg" alt="">
                        <div class="overlay"></div>
                        <span class="news-titolini">Because market research is part of the business plan</span>
                    </div>
                </div>
                <div class="col-4">
                    <div class="news-box">
                        <img src="../assets/img/news-3.jpg" alt="">
                        <div class="overlay"></div>
                        <span class="news-titolini">Working from home is now a trend</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'News',

    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.news-area{
    padding: 125px 0;

    .news-text{
        font-size: $textFontSize;
        color: $lightFontColor;
    }

    .m_button{
        background-color: $buttonIconColor;
        text-decoration: none;
        color: white;
    }

    .news-box{
        text-align: center;
        position: relative;
        color: white;
        overflow: hidden;
        border-radius: 7px;

        .overlay{
            display: inline-block;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.4);
        }

        img{
            border-radius: 7px;
        }

        .news-titolini{
            position: absolute;
            top: 80%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: $headingSize;
            font-weight: 600;
        }
    }
}
</style>