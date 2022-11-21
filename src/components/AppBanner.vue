<script>
export default{
    name:"AppBanner"
}
</script>

<template>
<div class="container">
    <div class="wrapper">
        <h4>Commerce Business</h4>
        <h2>Distant Mentoring Program</h2>
        <button>Download free guide -></button>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;
.container{
    background-image: url(../assets/images/home-3-hero-bg.jpg);
    background-position: center;
    background-size: cover;

    height: 500px;
    .wrapper{
        padding: 180px;
        text-align: center;
        h4{
            color: white;
            padding: 10px 0;
        }
        h2{
            color: white;
            font-size: 3rem;
            font-weight: lighter;
            padding:0 0 10px 0;
        }
        button{
            font-weight: 600;
            padding: 15px 20px;
            background-color: white;
            color: $green-color;
            border-radius: 5px;
            border: 0;
            cursor: pointer;
        }
    }
}

</style>