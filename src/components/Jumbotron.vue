<template>
    <div class="jumbotron">
        <div class="container">
            <div class="row">
                <div class="col-6 offset-6">
                    <div>
                        <div class="fusion">
                            Fusion & acquisitions
                        </div>
                        <h1>
                            Insurance Consulting
                        </h1>
                        <div class="form-type">
                            <input type="text" placeholder="Name">
                            <input class="more-info" type="text" placeholder="Email">
                            <input type="text" placeholder="Phone">
                            <input class="more-info" type="text" placeholder="More Info">
                            <i class="fas fa-angle-down down-arrow"></i>
                        </div>
                        <div class="buttons">
                            <a class="m_button get">
                                Get in touch
                            </a>
                            <a class="m_button read">
                                Read more
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Jumbotron'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.jumbotron{
    padding: 200px 0;

    .fusion{
        color: $buttonIconColor;
        text-transform: uppercase;
        margin-bottom: 10px;
        font-size: 20px;
    }

    h1{
        color: $mainFontColor;
        font-size: 70px;
        font-weight: 700;
        margin-bottom: 20px;
    }

    .form-type{
        margin-bottom: 20px;

        input{
            margin: 10px 10px 10px 0;
            background-color: #ccd2d2;
            border: none;
            padding: 10px;
            width: 250px;
            border-radius: 7px;
        }

        .more-info{
            position: absolute;
        }

        .down-arrow{
            position: relative;
            top: 0;
            left: 220px;
            cursor: pointer;
        }
    }

    .buttons a{
        text-decoration: none;
    }

    .get{
        background-color: $buttonIconColor;
        margin-right: 20px;
        color: white;
    }

    .read{
        color: $buttonIconColor;
    }
}
</style>