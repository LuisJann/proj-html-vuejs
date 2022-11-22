<script>
export default{
    name:"AppCta"
}
</script>

<template>
<div class="container bg-color-gray">
    <div class="wrapper d-flex flex-column align-item-center pd-bottom">
        <div class="courses">
            <span class="title">READ FOR MORE JOYMENT</span>
            <h2>Latest From <span class="green-text"> Our Blogs</span></h2>
        </div>
        <div class="card-section d-flex">
            <div class="card">
                <div class="box">
                    <img src="../assets/images/artist-blog-03-480x325.jpeg" alt="">
                </div>
                <span>ARTIST</span>
                <h4>Brush Strokes Energize Trees in Painting</h4>

                <div>
                    <span><i class="fa-regular fa-calendar"></i> May 15,2020 </span>
                    <span><i class="fa-solid fa-eye"></i> 688 views</span>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/artist-blog-01-480x325.jpg" alt="">
                </div>
                <span>ARTIST</span>
                <h4>Pocket-Sized Notebooks Hold Miniature Paintings</h4>

                <div>
                    <span><i class="fa-regular fa-calendar"></i> May 15, 2020 </span>
                    <span><i class="fa-solid fa-eye"></i> 603 views</span>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/artist-blog-02-480x325.jpg" alt="">
                </div>
                <span>ARTIST</span>
                <h4>Connection Between Self-Portraits and Identy</h4>

                <div>
                    <span><i class="fa-regular fa-calendar"></i> May 15, 2020 </span>
                    <span><i class="fa-solid fa-eye"></i> 397 views</span>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="container">
    <div class="wrapper">
        <img class="shape-2" src="../assets/images/maxcoach-shape-02.png" alt="">
        <img class="shape-9" src="../assets/images/maxcoach-shape-09.png" alt="">
        <div class="d-flex flex-column align-item-center margin-top cta-email">
            <h3>Subscribe <span class="green-text">Our Blogs</span></h3>
            <p>Enter your email address to register to our newsletter subscription delivered on a regular basis!</p>
            <div>
                <input type="email" placeholder="Enter your email
                "><button class="bold">Subscribe</button>
            </div>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;

.wrapper{
    position: relative;

    .shape-2{
        position: absolute;
        width: 100px;
        right: 100px;
        bottom: 50px;
        z-index: 999;
    }

    .shape-9{
        position: absolute;
        width: 150px;
        right: 100px;
        bottom: 60px;
        z-index: 1;
    }
}
.courses{
    text-align: center;
    margin-top: 30px;

    .title{
        font-size: .6rem;
    }

    h2{
        padding: 10px 0;
    }
}
.card{
    width: calc(100% / 3 - 20px);
    margin: 10px 20px;
    
    h4{
        padding-bottom: 15px;
        padding-top: 5px;
    }

    span{
        font-size: .6rem;
        color: $gray-color;
    }
    .box{
        width: 100%;


        img{
            width: 100%;
        }
    }
}

.cta-email{
    padding: 30px 0;
    h3{
        font-size: 2rem;
        padding-bottom: 10px;
    }

    p{
        font-size: .8rem;
        width: 40%;
        text-align: center;
        padding-bottom: 20px;
    }

    button{
            padding: 10px 7px;
            background-color: $green-color;
            color: white;
            border-radius: 0 5px 5px 0;
            border: 0;
            cursor: pointer;
    }

    input{
        width: 140px;
        padding: 10px 14px;
        border-radius: 5px 0 0 5px;
        background-color: $light-gray;
        border: 0;
    }
}
</style>