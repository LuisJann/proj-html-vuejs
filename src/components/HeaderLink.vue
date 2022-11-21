<script>
export default{
    name:"HeaderLink",
    props:{
        headerTitle: String,
        headerHref: String,
    }
}
</script>

<template>
    <li>
        <a href="{{ headerHref}}">{{ headerTitle}} <i class="fa-solid fa-chevron-down"></i></a>
    </li>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;
        li{
            padding: 0px 10px;
            display: flex;
            flex-wrap: nowrap;
            a{
                text-decoration: none;
                color: black;
                font-size: .7rem;
            }
            i{
                font-size: .5rem;
            }
        }

</style>