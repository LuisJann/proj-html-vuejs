<script>
import AppCta from './AppCta.vue';
export default{
    name:"AppFooter",
    components:{
        AppCta
    }
}
</script>

<template>
<AppCta />
<div class="container bg-black">
    <div class="wrapper d-flex space-between">
        <div>
            <h5>Address</h5>
            <span>lorem ipsum</span>
            <span>lorem ipsum</span>
            <span>lorem ipsum</span>
            <span class="social-icon"></span>
        </div>
        <div class="d-flex ">
            <ul>
                <h3>Explore</h3>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
            </ul>
            <ul>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
            </ul>
            <ul>
                <h3>Information</h3>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
                <li><a href="">prova</a></li>
            </ul>
        </div>
    </div>
</div>
</template>


<style lang="scss" scoped>
*{
    color: grey;
}
.bg-black{
    background-color: black;
}
    ul{
        padding: 0px 10px;
        li{
            list-style-type: none;
            a{
                text-decoration: none;
            }
        }
    }
</style>