<script>
export default{
    name:"FooterLink",
    props:{
        exploreTitle: String,
        exploreHref: String,
        informationTitle: String,
        InformationHref: String,
    }
}
</script>

<template>
    <li><a href="{{exploreHref}} {{informationHref}}">{{exploreTitle}} {{informationTitle}}</a></li>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;
li{
    list-style-type: none;
    margin: 5px 0;
            a{
                text-decoration: none;
                font-size: .7rem;
                color: $gray-color;
            }
        }

</style>