<script>
export default{
    name:"AppMain"
}
</script>

<template>
<div class="container">
    <div class="wrapper">
        <div class="d-flex center align-item-center">
            <div>
                <span>Lorem Ipsum</span>
                <h2>Lorem ipsum </h2>
                <p>lorem ipsum</p>
                <span>lorem ipsum</span>
            </div>
            <div>
                <div class="box"></div>
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
                <div class="box"></div>
            </div> 
            <div>
                <span>Lorem Ipsum</span>
                <h2>Lorem ipsum </h2>
                <p>lorem ipsum</p>
                <span>lorem ipsum</span>
            </div>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>

.container{
    padding: 30px 0;

    .stats{
        padding: 20px 0;
    }
    .box{
        width: 300px;
        height: 200px;
        background-color: beige;
    }
}

</style>