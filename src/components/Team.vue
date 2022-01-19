<template>
    <div class="team-area">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-9">
                    <div class="intestazione">
                        We like what we do
                    </div>
                    <div class="main-area-title">
                        <span class="main-area-title-detail-dark">Team</span>
                        of Experts
                    </div>
                    <div class="team-text mb-5">
                        Ethics and integrity are the bases on which our professionals build their careers. <br> They are fundamentals that become daily attitudes.
                    </div>
                    <div class=row>
                        <div class="col-6">
                            <div class="row mb-5">
                                <div class="col-4">
                                    <img src="../assets/img/team-1.jpg" alt="David Cooper">
                                </div>
                                <div class="col-8">
                                    <div class="team-title mb-2">
                                        David Cooper
                                    </div>
                                    <div class="team-text mb-3">
                                        CTO & CO-FOUNDER
                                    </div>
                                    <div class="socials">
                                        <i class="fab fa-facebook-f"></i>
                                        <i class="fab fa-twitter"></i>
                                        <i class="fab fa-linkedin-in"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="row mb-5">
                                <div class="col-4">
                                    <img src="../assets/img/team-2.jpg" alt="David Cooper">
                                </div>
                                <div class="col-8">
                                    <div class="team-title mb-2">
                                        Oliver Jones
                                    </div>
                                    <div class="team-text mb-3">
                                        CHIEF PROCUREMENT
                                    </div>
                                    <div class="socials">
                                        <i class="fab fa-facebook-f"></i>
                                        <i class="fab fa-twitter"></i>
                                        <i class="fab fa-linkedin-in"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="row">
                                <div class="col-4">
                                    <img src="../assets/img/team-3.jpg" alt="David Cooper">
                                </div>
                                <div class="col-8">
                                    <div class="team-title mb-2">
                                        Emma Lopez
                                    </div>
                                    <div class="team-text mb-3">
                                        CHIEF MARKETING
                                    </div>
                                    <div class="socials">
                                        <i class="fab fa-facebook-f"></i>
                                        <i class="fab fa-twitter"></i>
                                        <i class="fab fa-linkedin-in"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="row">
                                <div class="col-4">
                                    <img src="../assets/img/team-4.jpg" alt="David Cooper">
                                </div>
                                <div class="col-8">
                                    <div class="team-title mb-2">
                                        T. Johnson
                                    </div>
                                    <div class="team-text mb-3">
                                        CEO & PRESIDENT
                                    </div>
                                    <div class="socials">
                                        <i class="fab fa-facebook-f"></i>
                                        <i class="fab fa-twitter"></i>
                                        <i class="fab fa-linkedin-in"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="speech-container">
                        <div class="team-title mb-3">
                            President Speech
                        </div>
                        <div class="team-text mb-3">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent ut lacinia diam.  
                        </div>
                        <div class="team-text mb-3">
                            Vivamus efficitur et est quis posuere. Nulla sollicitudin vulputate dui, id pretium tortor congue eu. Integer aliquet justo eu quam volutpat ullamcorper.
                        </div>
                        <div class="team-text mb-3">
                            Duis ut hendrerit mauris. Phasellus faucibus ut enim vel tincidunt. Nunc venenatis a dui et laoreet.
                        </div>
                        <div class="team-title">
                            T. Johnson
                        </div>
                        <i class="fas fa-quote-right quote"></i>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Team'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.team-area{
    background-color: $mainFontColor;
    padding: 125px 0;
    color: white;

    .team-text{
        font-size: $textFontSize;
        color: $lightFontColor;
    }

    .team-title{
        font-size: $headingSize;
        font-weight: 600;
    }

    img{
        border-radius: 7px;
    }

    .socials i{
        background-color: #0e262d;
        color: #048383;
        width: 30px;
        height: 30px;
        line-height: 30px;
        text-align: center;
        border-radius: 50%;
        margin-right: 15px;
        cursor: pointer;
    }

    .speech-container{
        background-color: #048383;
        border-radius: 7px;
        padding: 30px 35px;
        position: relative;

        .quote{
            position: absolute;
            bottom: 25px;
            right: 25px;
            font-size: 22px;
            color: #036162;
        }
    }
}

</style>