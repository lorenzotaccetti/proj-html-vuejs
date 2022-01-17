<template>
    <div class="company-area">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-6">
                    <div class="intestazione">
                        About the network
                    </div>
                    <div class="company-title main-area-title">
                        <span class="dettaglio main-area-title-detail">The</span>
                        Company
                    </div>
                    <div class="company-text">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cras iaculis diam varius diam ultricies lacinia. Mauris lacus tellus, ultrices eu voluptat sit amet, finibus a ipsum.
                    </div>
                    <div class="company-text">
                        Curabitur convalis, diam a egestas iaculis, neque lorem interdum felis, in viverra lacus tortor in leo.
                    </div>
                </div>
                <div class="col-6">
                    <div class="row">
                        <div class="col-6">
                            <div class="titolino">
                                <i class="fas fa-award"></i>
                                <span>Tradition</span>
                            </div>
                            <div class="company-text">
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="titolino">
                                <i class="fas fa-lock"></i>
                                <span>Security</span>
                            </div>
                            <div class="company-text">
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="titolino">
                                <i class="far fa-edit"></i>
                                <span>Certificate</span>
                            </div>
                            <div class="company-text">
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="titolino">
                                <i class="fas fa-graduation-cap"></i>
                                <span>Expertise</span>
                            </div>
                            <div class="company-text">
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Company'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.company-area{
    background-color: $mainFontColor;
    padding: 125px 0;

    .company-title{
        color: white;

        .dettaglio{
            background-color: #0e262d;
        }
    }

    .company-text{
        color: $lightFontColor;
        font-size: $textFontSize;
        margin-bottom: 15px;
        padding: 0 15px 0 0;
    }

    .titolino{
        font-size: $headingSize;
        color: white;
        font-weight: 600;
        margin-bottom: 25px;

        i{
            color: $buttonIconColor;
            margin-right: 15px;
        }
    }
}
</style>