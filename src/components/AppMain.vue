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
<div class="container bg-color-gray">
    <div class="wrapper">
        <div class="d-flex center align-item-center">
            <div class="text-side">
                <span class="title">EVERYTHING IN <span class="bold">MAXCOACH</span></span>
                <h2>Learn about our <span class="green-text">Work Culture</span> at MaxCoach </h2>
                <p>Spread some time to visit our website or head office and discover our current courses, anrollment rpocedure, anda registration deadline. We're opening a new classes ecery beginning of each mounth</p>
                <p>Have questions? <a class="green-text" href="">Get Free Guide <i class="fa-solid fa-arrow-right"></i></a></p>
            </div>
            <div>
                <div class="box">
                    <img src="../assets/images/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
                    <img class="img-icon" src="../assets/images/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
                    <img class="shape-2" src="../assets/images/maxcoach-shape-02.png" alt="">
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
                    <img class="youtube-icon" src="../assets/images/icon-youtube-play.png" alt="">
                    <img class="shape-5" src="../assets/images/maxcoach-shape-05-150x150.png" alt="">
                    <img class="shape-7" src="../assets/images/maxcoach-shape-07-150x150.png" alt="">
                </div>
            </div> 
            <div class="text-side">
                <span class="title">How we work</span>
                <h2>Upgrade Your Skills <span class="green-text">Upgrade Your Life</span> </h2>
                <p>Opening up more opportunities in front of you to get the ticket to more enjoyable door in life. Getting equipped with new skills for new sets of insights into your carrer. MaxCoach accompany learnes in qvery stage of learning.</p>
                <p><a class="link bold" href="">Download free guidebook <i class="fa-solid fa-arrow-right"></i> </a></p>
            </div>
        </div>
    </div>
    <AppCard />
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;


.container{
    padding-top: 100px;
    position: relative;
    .text-side{
        margin: 0px 30px;
        width: 30%;

        .title{
            font-size: .6rem;
        }

        p{
            font-size: .6rem;
            color:$gray-color;
            margin: 10px 0;
        }

        // .link{
        //     color: ;
        // }
    }

    .link{
        color: black;
    }

    .stats{
        padding: 40px 20px;
        color: $green-color;
        text-align: center;
        font-size: 1.3rem;
        p{
            text-align: center;
            font-size: .6rem;
            color: $gray-color;
            margin: 0 10px;
        }
    }
    .box{
        width: 500px;
        height: 300px;
        background-color: beige;
        position: relative;

        .shape-5{
            position: absolute;
            width: 150px;
            left: -80px;
            top: 10px;
        }

        .shape-2{
            position: absolute;
            width: 90px;
            bottom: -90px;
            left: 400px;
        }

        .shape-7{
            position: absolute;
            width: 90px;
            bottom: -50px;
        }
        .img-icon{
            width: 150px;
            position: absolute;
            top: -30px;
            right: -30px;
            border-radius: 10px;
        }

        .youtube-icon{
            width: 60px;
            position: absolute;
            top: 50%;
            left: 42%;
            transition: .3s;
            cursor: pointer;

            &:hover{
                transform: scale(1.2);
            }
        }
        img{
            width: 100%;
        }
    }
}

</style>