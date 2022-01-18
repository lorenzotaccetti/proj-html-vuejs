<template>
    <div class="services-area">
        <div class="container">
            <div class="intestazione">
                Our business areas
            </div>
            <div class="main-area-title">
                Excellence in 
                <span class="main-area-title-detail-light">
                    Services
                </span>
            </div>
            <div class="row">
                <div class="col-8">
                    <div class="services-text">
                        We are leaders in providing consultancy services with a set of cutting-edge technologies and a team of experienced and renowned professionals. These are some options that you can hire.
                    </div>
                </div>
                <div class="col-2 offset-2 text-end">
                    <a class="m_button">
                        See All
                    </a>
                </div>
            </div>
            <div class="row mt-5">
                <div class="col-4">
                    <div class="box-services">
                        <div class="icona">
                            <i class="fas fa-network-wired"></i>
                        </div>
                        <div class="box-title">
                            Audit & Assurance
                        </div>
                        <div class="services-text">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        </div>
                        <div class="arrow">
                            <i class="fas fa-arrow-right"></i>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="box-services">
                        <div class="icona">
                            <i class="fas fa-briefcase"></i>
                        </div>
                        <div class="box-title">
                            Financial Advisory
                        </div>
                        <div class="services-text">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        </div>
                        <div class="arrow">
                            <i class="fas fa-arrow-right"></i>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="box-services">
                        <div class="icona">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <div class="box-title">
                            Analytics and M&A
                        </div>
                        <div class="services-text">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        </div>
                        <div class="arrow">
                            <i class="fas fa-arrow-right"></i>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="box-services">
                        <div class="icona">
                            <i class="fas fa-plane-departure"></i>
                        </div>
                        <div class="box-title">
                            Middle Marketing
                        </div>
                        <div class="services-text">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        </div>
                        <div class="arrow">
                            <i class="fas fa-arrow-right"></i>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="box-services">
                        <div class="icona">
                            <i class="fas fa-balance-scale"></i>
                        </div>
                        <div class="box-title">
                            Legal Consulting
                        </div>
                        <div class="services-text">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        </div>
                        <div class="arrow">
                            <i class="fas fa-arrow-right"></i>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="box-services">
                        <div class="icona">
                            <i class="fas fa-inbox"></i>
                        </div>
                        <div class="box-title">
                            Regulatory Risk
                        </div>
                        <div class="services-text">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        </div>
                        <div class="arrow">
                            <i class="fas fa-arrow-right"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Services'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';
.services-area{
    background-color: #eef4ed;
    padding: 125px 0;

    .dettaglio{
        background-color: #cbe2de;
        color: $buttonIconColor;
    }

    .services-text{
        font-size: $textFontSize;
        color: $lightFontColor;
    }

    .m_button{
        background-color: $buttonIconColor; 
        text-decoration: none;
        color: white;
    }

    .box-services{
        background-color: white;
        margin: 20px 10px;
        padding: 35px;
        border-radius: 7px;
        position: relative;

        .icona{
            color: $buttonIconColor;
            font-size: 30px;
            margin-bottom: 10px;
        }

        .box-title{
            font-size: $headingSize;
            color: $mainFontColor;
            font-weight: 600;
            margin-bottom: 15px;
        }

        .box-text{
            font-size: $textFontSize;
            color: $lightFontColor;
        }

        .arrow{
            color: $decorationColor;
            font-size: 20px;
            position: absolute;
            top: 30px;
            right: 30px;
            cursor: pointer;
        }
    }

}
</style>