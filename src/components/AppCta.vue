<script>
export default{
    name:"AppCta"
}
</script>

<template>
<div class="container">
    <div class="wrapper d-flex flex-column align-item-center">
        <div class="courses">
            <span>prova prova prova</span>
            <h2>Lorem ipsum dolor</h2>
        </div>
        <div class="card-section d-flex">
            <div class="card">
                <div class="box"></div>
                <h4>$40.<span>00</span></h4>
                <p>lorem ipsum dolor</p>
                <div>
                    <span>prova</span>
                    <span>prova</span>
                </div>
            </div>
            <div class="card">
                <div class="box"></div>
                <h4>$40.<span>00</span></h4>
                <p>lorem ipsum dolor</p>
                <div>
                    <span>prova</span>
                    <span>prova</span>
                </div>
            </div>
            <div class="card">
                <div class="box"></div>
                <h4>$40.<span>00</span></h4>
                <p>lorem ipsum dolor</p>
                <div>
                    <span>prova</span>
                    <span>prova</span>
                </div>
            </div>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    </div>
    <div class="wrapper">
        <div class="d-flex flex-column align-item-center">
            <span>More info</span>
            <h3>Subscribe <span>Our Blogs</span></h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo numquam, quasi dignissimos enim qui impedit nisi expedita assumenda sint maiores saepe hic doloremque quos, consequuntur est veniam. Dolores, dolorum pariatur.</p>
            <input type="text"><button>subscribe</button>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
.courses{
    text-align: center;
}
.card{
    margin: 10px 20px;
    background-color: aquamarine;
    .box{
        width: 200px;
        height: 100px;
        background-color: black;
    }
}
</style>