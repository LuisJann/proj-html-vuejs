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
                <h2>Learn about our <span class="green-text">Work Culture</span> at MaxCoach </h2>
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
                <h4>129+</h4>
                <p>ENROLLED LEARNERS</p>
            </div>
            <div>
                <h4>80</h4>
                <p>FINISCHED SESSIONS</p>
            </div>
            <div>
                <h4>4%</h4>
                <p>SATISFACTION RATE</p>
            </div>
        </div>
        <div class="d-flex center align-item-center">
            <div>
                <div class="box">
                    <img src="../assets/images/stock-full-hd-11-670x450.jpg" alt="">
                </div>
            </div> 
            <div class="text-side">
                <span>How we work</span>
                <h2>Upgrade Your Skills <span class="green-text">Upgrade Your Life</span> </h2>
                <p>Opening up more opportunities in front of you to get the ticket to more enjoyable door in life. Getting equipped with new skills for new sets of insights into your carrer. MaxCoach accompany learnes in qvery stage of learning.</p>
                <span><a href="">Download free guidebook -></a></span>
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
        margin: 0px 15px;
        width: 30%;
        span{
            color:$grey-color;
            font-weight: bold;
        }

        p{
            font-size: .8rem;
            color:$grey-color;
            margin: 10px 0;
        }
    }

    .stats{
        padding: 20px 10px;
        color: $green-color;
        text-align: center;
        font-size: 1.3rem;
        p{
            text-align: center;
            font-size: .6rem;
            color: $grey-color;
            margin: 0 10px;
        }
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