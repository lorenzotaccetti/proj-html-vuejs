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
                    <span class="number-decoration">01</span>
                </div>
                <div class="process-title">Collection of information</div>
                <div class="process-text">
                    Lorem ipsum dolor, sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    <span class="number-decoration">02</span>
                </div>
                <div class="process-title">
                    Strategic planning
                </div>
                <div class="process-text">
                    Lorem ipsum dolor, sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    <span class="number-decoration">03</span>
                </div>
                <div class="process-title">
                    Assignment of responsibilities
                </div>
                <div class="process-text">
                    Lorem ipsum dolor, sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    <span class="number-decoration">04</span>
                </div>
                <div class="process-title">
                    Formatting process
                </div>
                <div class="process-text">
                    Lorem ipsum dolor, sit amet consectetur.
                </div>
            </div>
            <div class="col-2">
                <div class="number">
                    <span class="number-decoration">05</span>
                </div>
                <div class="process-title">
                    Continuity formalization
                </div>
                <div class="process-text">
                    Lorem ipsum dolor, sit amet consectetur.
                </div>
            </div>
        </div>
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

    .number{
        color: $buttonIconColor;
        font-weight: 600;
        background-color: #d9ebed;
        width: 40px;
        height: 40px;
        line-height: 40px;
        border-radius: 50%;
        display: inline-block;

        // .number-decoration{
        //     display: flex;
        //     align-items: center;
        //     justify-content: center;
        // }

        // .number-decoration::before{
        //     display: inline-block;
        //     content: '';
        //     width: 300px;
        //     height: 5px;
        //     background-color: #d9ebed;
        // }
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