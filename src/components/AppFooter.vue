<script>
import AppCta from './AppCta.vue';
import FooterLink from './FooterLink.vue';
export default{
    name:"AppFooter",
    components:{
        AppCta,
        FooterLink
    },
    data(){
        return{
            linksFooterExplore:[
                {
                    title: "Start here",
                    href:"/starhere"
                },
                {
                    title: "Blog",
                    href:"/blog"
                },
                {
                    title: "About us",
                    href:"/aboutus"
                },
                {
                    title: "Success story",
                    href:"/successtory"
                },
                {
                    title: "Courses",
                    href:"/courses"
                },
                {
                    title: "contact us",
                    href:"/contactus"
                },
            ],
            linksFooterInformation:[
                {
                    title: "Membership",
                    href:"/membership"
                },
                {
                    title: "Purchase guide",
                    href:"/purchaseguide"
                },
                {
                    title: "Privacy policy",
                    href:"/privacypolicy"
                },
                {
                    title: "Term of service",
                    href:"/termofservice"
                },
            ]
        }
    }
}
</script>

<template>
<AppCta />
<div class="container bg-black">
    <div class="wrapper d-flex space-between">
        <div class="address">
            <h4>Address</h4>
            <p>382 NE 191st # 87394 Miami, FL 33179-3899</p>
            <p>+1(305)547-9909 (9am - 5pcEST,Monday - Friday)</p>
            <p>support@maxcoach.com</p>
            <p class="social-icon"></p>
            <div class="icon">
                <i class="fa-brands fa-square-facebook"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-linkedin"></i>
            </div>
        </div>
        <div class="d-flex ">
            <ul>
                <h4>Explore</h4>
                <FooterLink v-for="(link, index) in linksFooterExplore" :key="index" :exploreTitle="link.title" :exploreHref="link.href" />
            </ul>
            <ul>
                <h4>Information</h4>
                <FooterLink v-for="(link, index) in linksFooterInformation" :key="index" :informationTitle="link.title" :InformationHref="link.href" />
            </ul>
        </div>
    </div>
</div>
</template>


<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;
.address{
    h4{
        color: white;
        padding-top: 30px;
    }
    p{
        color: $gray-color;
        font-size: .8rem;
        padding: 10px 0;
    }
    .icon{
        color: $gray-color;
        
        i{
            margin-right: 15px;
            font-size: 1.2rem;
        }
    }
}
.bg-black{
    background-color: black;
    padding: 30px 0;
}
    ul{
        margin: 0 20px;

        h4{
            color: white;
            padding-top: 30px;
        }
    }
</style>