<template>
    <footer>
        <div class="container">
            <div class="merch">
                <img src='../assets/img/buy-comics-digital-comics.png' alt="">
                <h4>Digital Comics</h4>
            </div>
            <div class="merch">
                <img src='../assets/img/buy-comics-digital-comics.png' alt="">
                <h4>Digital Comics</h4>
            </div>
            <div class="merch">
                <img src='../assets/img/buy-comics-digital-comics.png' alt="">
                <h4>Digital Comics</h4>
            </div>
            <div class="merch">
                <img src='../assets/img/buy-comics-digital-comics.png' alt="">
                <h4>Digital Comics</h4>
            </div>
            <div class="merch">
                <img src='../assets/img/buy-comics-digital-comics.png' alt="">
                <h4>Digital Comics</h4>
            </div>

        </div>
    </footer>
</template>

<script>
export default {
    name:'FooterTop',
}
</script>

<style lang="scss" scoped>
    @import '../assets/style/global.scss';
    footer{
        background-color: $mainColor;

        div{
            height: 250px;

            .merch{
                display: flex;
                align-items: center;

                img{
                    width: 70px;
                }

                h4{
                    color: white;
                    font-weight: 400;
                    padding: 0 20px;
                }
            }
        }
    }
</style>