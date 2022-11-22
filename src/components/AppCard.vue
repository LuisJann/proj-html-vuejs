<script>
export default{
    name:"AppCard"
}
</script>

<template>
<div class="container">
    <div class="wrapper d-flex flex-column align-item-center">
        <div class="courses">
            <p>JOIN MAXCOACH AT BEST</p>
            <h2>Latest Online <span class="green-text">Courses</span></h2>
        </div>
        <div class="card-section d-flex">
            <div class="card">
                <div class="box">
                    <img src="../assets/images/course-02-480x298.jpg" alt="">
                </div>
                <div class="text-card">
                    <h4>$40.<span class="cents">00</span></h4>
                    <p class="bold">Learning to Write as a Professional Author</p>
                    <div class="icon-side">
                        <span><i class="fa-regular fa-file"></i> 20 Lessons </span>
                        <span><i class="fa-regular fa-user"></i> 50 students</span>
                    </div>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/stock-full-hd-03-480x298.jpg" alt="">
                </div>
                <div class="text-card">
                    <h4>$0.<span class="cents">00</span></h4>
                    <p class="bold">Customer-centric Info-Tech Strategies</p>
                    <div class="icon-side">
                        <span><i class="fa-regular fa-file"></i> 24 Lessons </span>
                        <span><i class="fa-regular fa-user"></i> 769 Students</span>
                    </div>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/stock-full-hd-04-480x298.jpg" alt="">
                </div>
                <div class="text-card">
                    <h4>$19.<span class="cents">00</span></h4>
                    <p class="bold">Open Programming Courses for Everyone: Python</p>
                    <div class="icon-side">
                        <span><i class="fa-regular fa-file"></i> 17 Lessons </span>
                        <span><i class="fa-regular fa-user"></i> 62 Students</span>
                    </div>
                </div>
            </div>
        </div>
        <div class="d-flex align-item-center slide-icon">
            <i class="fa-solid fa-circle icon selected"></i>
            <i class="fa-solid fa-circle icon"></i>
            <i class="fa-solid fa-circle icon"></i>
            <i class="fa-solid fa-circle icon"></i>
            <i class="fa-solid fa-circle icon"></i>
        </div>
        <p class="preference">Control your personal preference settings to get notified about appropriate courses. <a class="bold" href="">View all course <i class="fa-solid fa-arrow-right"></i></a></p>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;
.courses{
    text-align: center;
    p{
        font-size: .6rem;
        padding-bottom: 10px;
    }
    h2{
        padding-bottom: 10px;
    }
}
.card{
    width: calc(100% / 3 - 20px);
    margin: 10px 20px;
    background-color: white;
    padding-bottom: 20px;
    transition: .3s;
    cursor: pointer;

    &:hover{
        box-shadow: 2px 1px 5px 3px rgba(0,0,0,0.44);
    }


    h4{
        font-size: 1.2rem;
        color: $green-color;
        padding-bottom: 10px;
        .cents{
            font-size: .8rem;
        }
    }

    p{
        padding-bottom: 10px;
    }

    .text-card{
        padding: 15px;
        width: 80%;
        font-size: .7rem;
    }
    .box{
        width: 100%;


        img{
            width: 100%;
            padding-bottom: 10px;
        }
    }
    .icon-side{
        color: $gray-color;
        font-size: .6rem;

        span{
            padding: 10px 0;
        }
    }

}
.preference{
    padding: 20px;
    width: 50%;
    text-align: center;
    font-size: .7rem;
    font-weight: lighter;
    a{
        color: black;
    }
}
.slide-icon{
    height: 20px;
    .icon{
        padding: 8px;
        font-size: .4rem;
        color:$gray-color ;
    }
    
    .selected{
        font-size: .6rem;
        color: black;
        
    
    }
}
</style>