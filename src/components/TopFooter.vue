<template>
    <div class="top-footer">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-3">
                    <div class="text-logo mb-4">
                        <span class="nex_title">N E X</span>
                        G E N
                    </div>
                    <div class="footer-text mb-4">
                        A Functional HTML Template for Corporate & Business.
                    </div>
                    <div class="footer-text mb-3">
                        <i class="fas fa-phone-alt"></i>
                        <span>+1 (305) 1234-5678</span>
                    </div>
                    <div class="footer-text mb-3">
                        <i class="fas fa-envelope"></i>
                        <span>hello@example.com</span>
                    </div>
                    <div class="footer-text mb-4">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>Main Avenue, 987</span>
                    </div>
                    <div class="m_button">
                        Get in touch
                    </div>
                </div>
                <div class="col-3">
                    <div class="footer-box">
                        <div class="footer-title mb-3">
                            About
                        </div>
                        <div class="footer-list">
                            <div 
                            class="mb-3 element-list" 
                            v-for="(element, index) in about" 
                            :key="index">
                                <i class="fas fa-chevron-right"></i>
                                {{element}}
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="footer-box">
                        <div class="footer-title mb-3">
                            Services
                        </div>
                        <div class="footer-list">
                            <div 
                            class="mb-3 element-list" 
                            v-for="(element, index) in services" 
                            :key="index">
                                <i class="fas fa-chevron-right"></i>
                                {{element}}
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="footer-box">
                        <div class="footer-title mb-3">
                            Support
                        </div>
                        <div class="footer-list">
                            <div 
                            class="mb-3 element-list" 
                            v-for="(element, index) in support" 
                            :key="index">
                                <i class="fas fa-chevron-right"></i>
                                {{element}}
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
        name: 'TopFooter',
        props: {
            about: Object,
            services: Object,
            support: Object
        }
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.top-footer{
    background-color: $mainFontColor;
    padding: 125px 0;
    color: white;

    .m_button:hover{
        background-color: $buttonIconColor;
    }

    .text-logo{
        font-size: 20px;
        font-weight: 600;

        .nex_title{
            background-color: #0e262d;
            border-color: #0e262d; 
            color: #0ba1a4; 
            margin-right: 5px;
        }
    }

    .footer-text{
        color: $lightFontColor;
        font-size: $textFontSize;

        i{
            margin-right: 15px;
        }
    }

    .footer-box{
        background-color: #191920;
        padding: 20px 40px;
        border-radius: 7px;

        .footer-title{
            font-size: $headingSize;
            font-weight: 600;
        }

        .footer-list{
            color: $lightFontColor;
            font-size: $textFontSize;

            .element-list{
                cursor: pointer;

                &:hover{
                    text-decoration: underline;
                }
            }

            i{
                padding-right: 10px;
            }
        }
    }
}

</style>