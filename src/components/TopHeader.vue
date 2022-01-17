<template>
    <div class="top-header">
        <div class="container disposition">
            <div class="orario">
                <i class="fas fa-clock"></i>
                <span>
                    Open Hours: Mon - Sat - 9.00 - 18.00
                </span>
            </div>
            <div class="numero-telefonico">
                <i class="fas fa-phone-alt"></i>
                <span>
                    +1 (305) 1234-5678
                </span>
            </div>
            <div class="mail">
                <i class="fas fa-envelope"></i>
                <span>
                    hello@example.com
                </span>
            </div>
            <div class="socials">
                <a href="#">
                    <i class="fab fa-facebook-f"></i>
                </a>
                <a href="#">
                    <i class="fab fa-twitter"></i>
                </a>
                <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                </a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'TopHeader'
    }
</script>

<style lang="scss" scoped>
@import '../style/generals.scss';
@import '../style/variables.scss';

.top-header{
    background-color: #21333e;
    color: $lightFontColor;
    font-size: 13px;
    padding: 12px 0;
    font-weight: lighter;

    .disposition{
        display: flex;
        align-items: center;

        .orario{
            flex-grow: 1;

            i{
                padding-right: 8px;
            }
        }

        .numero-telefonico{
            padding-right: 40px;

            i{
                padding-right: 8px;
            }
        }

        .mail{
            i{
                padding-right: 8px;
            }
        }

        .socials i{
            padding-left: 40px;
            color: $lightFontColor;
            text-decoration: none;
        }
    }
}
</style>