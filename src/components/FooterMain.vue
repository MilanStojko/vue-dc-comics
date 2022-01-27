<template>
    <footer>
        <div class="container">
            <nav>
                <div class="lista">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">Tv</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop Dc Collectibles</a></li>
                    </ul>
                </div>
                <div class="lista">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="">Terms of Use</a></li>
                        <li><a href="">Privacy policy (New)</a></li>
                        <li><a href="">Ad Choice</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="lista">
                    <h3>Sites</h3>
                    <ul>
                        <li><a href="">DC</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">Dc Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>                        
                    </ul>
                </div>
            </nav>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </footer>
</template>

<script>
export default {
    name:'FooterMain',
}
</script>

<style lang="scss" scoped>
    @import '../assets/style/global.scss';
    footer{
        background-image: url("../assets/img/footer-bg.jpg");
        background-position: center;
        background-size: cover;
        height: 400px;
        overflow-y: hidden;

        .container{
            img{
                height: 600px;
                width: 600px;
                margin: -100px 0; 
            }
            nav{
                display: flex;

                h3{
                    font-weight: bold;
                    color: white;
                    
                }
            }
        }
    }
</style>