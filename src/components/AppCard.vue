<script>
export default{
    name:"AppCard"
}
</script>

<template>
<div class="container">
    <div class="wrapper d-flex flex-column align-item-center">
        <div class="courses">
            <span>JOIN MAXCOACH AT BEST</span>
            <h2>Latest Online <span class="green-text">Courses</span></h2>
        </div>
        <div class="card-section d-flex">
            <div class="card">
                <div class="box">
                    <img src="../assets/images/course-02-480x298.jpg" alt="">
                </div>
                <h4>$40.<span class="cents">00</span></h4>
                <p>Learning to Write as a Professional Author</p>
                <div>
                    <span>20 Lessons</span>
                    <span>50 students</span>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/stock-full-hd-03-480x298.jpg" alt="">
                </div>
                <h4>$0.<span class="cents">00</span></h4>
                <p>Customer-centric Info-Tech Strategies</p>
                <div>
                    <span>24 Lessons</span>
                    <span>769 Students</span>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/stock-full-hd-04-480x298.jpg" alt="">
                </div>
                <h4>$19.<span class="cents">00</span></h4>
                <p>Open Programming Courses for Everyone: Python</p>
                <div>
                    <span>17 Lessons</span>
                    <span>62 Students</span>
                </div>
            </div>
        </div>
        <p>Control your personal preference settings to get notified about appropriate courses. <span><a href="">View all course -></a></span></p>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;
.courses{
    text-align: center;
}
.card{
    width: calc(100% / 3 - 20px);
    margin: 10px 20px;


    h4{
        color: $green-color;
        .cents{
            font-size: .8rem;
        }
    }

    .box{
        width: 100%;


        img{
            width: 100%;
            padding-bottom: 10px;
        }
    }
}
</style>