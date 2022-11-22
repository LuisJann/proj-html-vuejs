<script>
import HeaderLink from './HeaderLink.vue';

export default{
    name:"AppHeader",
    components:{
        HeaderLink
    },
    props:{
        headerTitle: String,
        headerHref: String,
    },
    data(){
        return{
            linksHeader:[
                {
                    title:"Home",
                    href:"/home"
                },
                {
                    title:"Pages",
                    href:"/pages"
                },
                {
                    title:"Courses",
                    href:"/coures"
                },
                {
                    title:"Features",
                    href:"/features"
                },
                {
                    title:"Blog",
                    href:"/blog"
                },
                {
                    title:"Shop",
                    href:"/shop"
                },
            ]
        }
    }
}
</script>

<template>
    <div class="container d-flex space-between align-item-center">
        <div class="left-menu">
            <ul class="d-flex">
                <HeaderLink v-for="(link, index) in linksHeader" :key="index" :headerTitle="link.title" :headerHref="link.href" />
            </ul>
        </div>
        <div class="logo">
            <img src="../assets/images/dark-logo.png" alt="">
        </div>
        <div class="right-menu">
            <i class="fa-solid fa-cart-shopping"><span class="product">0</span></i>
            <i class="fa-regular fa-circle-user"></i>
            <div class="input-side">
                <input type="text" placeholder="Search..."><i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;

.container{
    padding: 15px;
    .left-menu{
        width: calc(100% / 3);
        ul{
            list-style-type: none;
        }
    }

    .logo{
        text-align: center;
        width: calc(100% / 3);
        img{
            width: 150px;
            cursor: pointer;
        }
    }
    
    .right-menu{
        width: calc(100% / 3);
        text-align: center;
        display: flex;
        align-items: center;
        justify-content: flex-end;

        i{
            padding: 0 10px;
        }
        .input-side{
            display: flex;

            input{
                padding: 6px;
                background-color: $light-gray;
                border: 0;
                border-radius: 10px 0 0 10px;
            }
            i{
                padding: 5px;
                border-radius: 0 10px 10px 0;
                background-color: $light-gray;
                color: $green-color;
                position: relative;
            }
        }
        .product{
            background-color: $green-color;
            color: white;
            border-radius: 50px;
            font-size: .6rem;
            padding: 3px;
            width: 15px;
            height: 15px;
            position: absolute;
            top:10px;
        }
        span{
            padding: 0 5px;
        }
    }
}

</style>