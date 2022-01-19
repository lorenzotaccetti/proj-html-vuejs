<template>
    <div class="process-area">
        <div class="intestazione">
            How it works in practice
        </div>
        <div class="main-area-title">
            <span class="main-area-title-detail-light">Process</span> 
            Management
        </div>
        <div class="process-text pb-3">
            We work with innovative methodologies to ensure that the entire reformatting process is done from start to finish as planned.
        </div>
        <div class="row mt-5">
            <div class="col-2 offset-1">
                <div class="number">
                    01
                </div>
                <div class="process-title">Collection of information</div>
                <div class="process-text">
                    Lorem ipsum dolor sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    02
                </div>
                <div class="process-title">
                    Strategic planning
                </div>
                <div class="process-text">
                    Lorem ipsum dolor sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    03
                </div>
                <div class="process-title">
                    Assignment of responsibilities
                </div>
                <div class="process-text">
                    Lorem ipsum dolor sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    04
                </div>
                <div class="process-title">
                    Formatting process
                </div>
                <div class="process-text">
                    Lorem ipsum dolor sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    05
                </div>
                <div class="process-title">
                    Continuity formalization
                </div>
                <div class="process-text">
                    Lorem ipsum dolor sit amet consectetur.
                </div>
            </div>
        </div>
        <div class="dettaglio"></div>
    </div>
</template>

<script>
    export default {
        name: 'Process'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.process-area{
    text-align: center;
    padding: 125px 0;
    position: relative;

    .number{
        position: relative;
        color: $buttonIconColor;
        font-weight: 600;
        background-color: #d9ebed;
        width: 40px;
        height: 40px;
        line-height: 40px;
        border-radius: 50%;
        display: inline-block;
        z-index: 3;
    }

    .dettaglio{
        width: 100%;
        height: 5px;
        background-color: #d9ebed;
        position: absolute;
        top: 56%;
        left: 0;
        display: none;
        z-index: 0;
    }

    @media screen and (min-width: 1071px) {
        .dettaglio {
            display: inline-block;
        }
    }

    @media screen and (min-width: 1952px) {
        .dettaglio{
            display: none;
        }
    }

    .process-text{
        font-size: $textFontSize;
        color: $lightFontColor;
    }

    .process-title{
        font-size: $headingSize;
        color: $mainFontColor;
        font-weight: 600;
        margin: 15px 0;
    }

}
</style>