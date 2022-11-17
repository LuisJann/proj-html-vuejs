<script>
export default{
    name:"AppHeader"
}
</script>

<template>
    <div class="container d-flex space-between">
        <div class="left-menu">
            <ul class="d-flex">
                <li>
                    <a href="">prova</a>
                </li>
                <li>
                    <a href="">prova</a>
                </li>
                <li>
                    <a href="">prova</a>
                </li>
                <li>
                    <a href="">prova</a>
                </li>
                <li>
                    <a href="">prova</a>
                </li>
                <li>
                    <a href="">prova</a>
                </li>
            </ul>
        </div>
        <div class="logo">
            <h1>logo</h1>
        </div>
        <div class="right-menu">
            <span>prova</span>
            <span>prova</span>
            <span>prova</span>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.container{
    .left-menu{
        padding: 0 50px;
        
        ul{
            list-style-type: none;

            li{
                padding: 0px 10px;

                a{
                    text-decoration: none;
                    color: black;
                }
            }
        }
    }

    .logo{
        text-align: center;
        width: 100%;
    }
    
    .right-menu{
        padding: 0 50px;

        span{
            padding: 0 10px;
        }
    }
}

</style>