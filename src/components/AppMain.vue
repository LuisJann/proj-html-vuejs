<script>
import AppCard from './AppCard.vue';
export default{
    name:"AppMain",
    components:{
        AppCard,
    }
}
</script>

<template>
<div class="container">
    <div class="wrapper">
        <div class="d-flex center align-item-center">
            <div class="text-side">
                <span>EVERYTHING IN <span>MAXCOACH</span></span>
                <h2>Learn about our <span class="work-culture">Work Culture</span> at MaxCoach </h2>
                <p>Spread some time to visit our website or head office and discover our current courses, anrollment rpocedure, anda registration deadline. We're opening a new classes ecery beginning of each mounth</p>
                <span>Have questions? <a href="">Get Free Guide -></a></span>
            </div>
            <div>
                <div class="box">
                    <img src="../assets/images/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
                </div>
            </div>            
        </div>
        <div class="d-flex center align-item-center stats">
            <div>
                <h4>129</h4>
                <p>lorem ipsum</p>
            </div>
            <div>
                <h4>129</h4>
                <p>lorem ipsum</p>
            </div>
            <div>
                <h4>129</h4>
                <p>lorem ipsum</p>
            </div>
        </div>
        <div class="d-flex center align-item-center">
            <div>
                <div class="box">
                </div>
            </div> 
            <div>
                <span>Lorem Ipsum</span>
                <h2>Lorem ipsum </h2>
                <p>lorem ipsum</p>
                <span>lorem ipsum</span>
            </div>
        </div>
    </div>
    <AppCard />
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;

.container{
    padding: 30px 0;
    .text-side{
        margin-right: 30px;
        width: 30%;
        span{
            color:$grey-color;
            font-weight: bold;
        }
        .work-culture{
            color:$green-color;
            font-weight: lighter;
        }
        p{
            font-size: .8rem;
            color:$grey-color;
            margin: 10px 0;
        }
    }

    .stats{
        padding: 20px 0;
    }
    .box{
        width: 300px;
        height: 200px;
        background-color: beige;
        img{
            width: 300px;
            height: 200px;
            object-fit: cover;
            
        }
    }
}

</style>