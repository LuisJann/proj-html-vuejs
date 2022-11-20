<script>
export default{
    name:"AppCta"
}
</script>

<template>
<div class="container">
    <div class="wrapper d-flex flex-column align-item-center">
        <div class="courses">
            <span>READ FOR MORE JOYMENT</span>
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
                    <span>May 15,2020 </span>
                    <span> 688 views</span>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/artist-blog-01-480x325.jpg" alt="">
                </div>
                <span>ARTIST</span>
                <h4>Pocket-Sized Notebooks Hold Miniature Paintings</h4>

                <div>
                    <span>May 15, 2020 </span>
                    <span>603 views</span>
                </div>
            </div>
            <div class="card">
                <div class="box">
                    <img src="../assets/images/artist-blog-02-480x325.jpg" alt="">
                </div>
                <span>ARTIST</span>
                <h4>Connection Between Self-Portraits and Identy</h4>

                <div>
                    <span>May 15, 2020 </span>
                    <span> 397 views</span>
                </div>
            </div>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    </div>
    <div class="wrapper">
        <div class="d-flex flex-column align-item-center margin-top">
            <h3>Subscribe <span class="green-text">Our Blogs</span></h3>
            <p>Enter your email address to register to our newsletter subscription delivered on a regular basis!</p>
            <div>
                <input type="text" placeholder="Enter your email"><button>subscribe</button>
            </div>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
.courses{
    text-align: center;
    margin-top: 30px;
}
.card{
    width: calc(100% / 3 - 20px);
    margin: 10px 20px;
    .box{
        width: 100%;


        img{
            width: 100%;
        }
    }
}
</style>