<template>
    <main>
        <div class="container">
            <h1>->Content Goes Here 'freccietta'- </h1>
        </div>
    </main>
</template>

<script>
export default {
    name: 'Main'
};
</script>

<style lang="scss" scoped>
    @import '../assets/style/global.scss';
    main{
        background-color: #1c1c1c;

        div{
            min-height: 200px;

            h1{
                color: white;
            }
        }
    }
</style>