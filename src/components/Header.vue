<template>
    <header>
        <div class="container">
                <img src="../assets/img/dc-logo.png" alt="">
            <nav>
                <ul>
                    <li v-for="(link, index) in menu" :key="index">
                        <a href="#">
                            <span :class="{'active': link.active}">{{link.text}}</span>
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name:'Header',
    data(){
        return{
            menu:[
                {
                    text:"CHARACTERS",
                    url:'#',
                    active: false,
                },
                {
                    text:"COMICS",
                    url:'#',
                    active: true,
                },
                {
                    text:"MOVIES",
                    url:'#',
                    active: false,
                },
                {
                    text:"TV",
                    url:'#',
                    active: false,
                },
                {
                    text:"GAMES",
                    url:'#',
                    active: false,
                },
                {
                    text:"COLLECTIBLES",
                    url:'#',
                    active: false,
                },
                {
                    text:"VIDEO",
                    url:'#',
                    active: false,
                },
                {
                    text:"FANS",
                    url:'#',
                    active: false,
                },
                {
                    text:"NEWS",
                    url:'#',
                    active: false,
                },
                {
                    text:"SHOP",
                    url:'#',
                    active: false,
                },
            ]
        }
    }
};
</script>

<style lang="scss" scoped>
    @import '../assets/style/global.scss';
    header{
        div{
            height: 150px;
        }  
    }
    nav{
        height: 100%;

        ul{
            height: 100%;
            list-style-type: none;
            display: flex;
            justify-content: center;
            align-items: center;

            li{
                height: 100%;
                display: flex;
                align-items: center;

                    &:hover{
                    background-color: whitesmoke;
                    }

                a{
                    text-decoration: none;
                    color: black;
                    padding: 0 15px;
                    font-weight: 550;


                    span.active{
                        border-bottom: solid 5px $mainColor;
                        color: $mainColor;
                        padding: 60px 0;
                    }

                    
                }
            }
        }
    }
</style>
