<template>
    <footer>
        <div class="container">
            <div class="button">
                <a href="">
                    <h2>SING-UP NOW!</h2>
                </a>
            </div>
            <div class="right">
                <a href="">
                    <h2>FOLLOW US</h2>
                </a>
                <ul>
                    <li><a href="">
                        <img src="../assets/img/footer-facebook.png" alt="">
                    </a></li>
                    <li><a href="">
                        <img src="../assets/img/footer-twitter.png" alt="">
                    </a></li>
                    <li><a href="">
                        <img src="../assets/img/footer-youtube.png" alt="">
                    </a></li>
                    <li><a href="">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </a></li>
                    <li><a href="">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </a></li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name:'FooterInfo',
}
</script>

<style lang="scss" scoped>
    @import '../assets/style/global.scss';
    footer{
        background-color: #303030;

        div{
            height: 100px;
            .button{
                display: flex;
                align-items: center;

                a{
                    text-decoration: none;
                    color: white;

                    h2{
                    text-decoration: none;
                    border: 2px solid $mainColor;
                    padding: 15px;
                    }
                }
            }
            .right{
                display: flex;
                align-items: center;
                a{
                    text-decoration: none;
                    color: $mainColor;
                }
                ul{
                    display: flex;
                    list-style: none;
                    
                    li{
                        padding: 0 10px;
                    }
                }
            }

        }

    }

</style>