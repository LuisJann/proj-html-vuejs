<script>
export default{
    name:"AppTestimonial"
}
</script>

<template>
<div class="container">
    <div class="wrapper">
        <div class="d-flex center align-item-center">
            <div class="text-side">
                <span class="title">TESTIMONIALS</span>
                <h3>Why Do People <span class="green-text">*Hearts*</span> Us?</h3>
                <p>Seeking for verbals of our service quality? find them here. Everythings is transparent and straightforward fors your sense of justification </p>
                <span><a class="bold" href="">View all <i class="fa-solid fa-arrow-right"></i></a></span>
            </div>
            <div>
                <div class="box-card">
                    <div class="card-bg">
                        <h5 class="bold">The MaxCoach team works really hard to ensure high level of quality</h5>
                        <p>Im happy with their arrangement of lessons anda subject. They</p>
                        <div class="testimonial d-flex">
                            <div class="user">
                                <img src="../assets/images/testimonial-avata-02.jpg" alt="">
                            </div>
                            <div class="name">
                                <h5>MINA HOLLANCE</h5>
                                <span>/ Freelancer</span>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                        <h5 class="bold">Professional team of specialists and passionate mentors at reach</h5>
                        <p>I need to get certification for English proficiency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.</p>
                        <div class="testimonial d-flex">
                            <div class="user">
                                <img src="../assets/images/testimonial-avata-01.jpg" alt="">
                            </div>
                            <div class="name">
                                <h5>MADLEY PONDOR</h5>
                                <span>/ IT specialist</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="d-flex center align-item-center">
            <div>
                <div class="box">
                    <img src="../assets/images/home-3-team-image.png" alt="">
                </div>
            </div>
            <div class="text-side">
                <span>EVERYTHINGS IN <span>MAXCOACH</span></span>
                <h3>We're Here To <span class="green-text">Transform</span> You!</h3>
                <p>As learnes, people can enjoy great companionship from MaxCoach mentors and educators. We can hel you develop and grow at your best. </p>
                <button>Get free Guide</button>
            </div>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use"../styles/partials/variables.scss" as*;

.text-side{
    width: 30%;
    margin: 0 15px;

    button{
            padding: 10px 7px;
            background-color: $green-color;
            color: white;
            border-radius: 5px;
            border: 0;
            cursor: pointer;
    }

    .title{
        font-size: .6rem;
    }

    h3{
        padding-top: 10px;
    }

    p{
        font-size: .6rem;
        padding: 10px 0;
        color: $gray-color;
    }

    span{
        a{
            color: black;
            font-size: .6rem;
        }
    }
}
.box{
    width: 250px;
    height: 250px;
    margin: 50px 20px;

    img{
        width: 100%;
    }

}

.box-card{
    position: relative;
    margin-left: 50px;
    margin-top: 20px;
    .card-bg{
        width: 250px;
        height: 300px;
        background-color: white;
        padding: 15px;
        position: relative;
        opacity: .3;
        box-shadow: 2px 1px 5px 3px rgba(0,0,0,0.44);
        border-radius: 5px;

        h5{
            
        }

        p{
            font-size: .6rem;
            padding: 5px;
            color: $gray-color;
        }

        .testimonial{
            position: absolute;
            bottom: 5px;

            .name{
                h5,
                span{
                    font-size: .6rem;
                    padding-left: 5px;
                }
            }
            

            .user{
                img{
                    object-fit: contain;
                    width: 50px;
                    border-radius: 50%;
                }
            }
        }


    }
    .card{
        width: 350px;
        height: 180px;
        margin: 0 auto;
        position: absolute;
        left: -50px;
        top: 55px;
        padding: 10px;
        box-shadow: 2px 1px 5px 3px rgba(0,0,0,0.44);
        border-radius: 5px;

        background-color: white;

        h5{
            padding-top: 5px;
        }

        p{
            font-size: .6rem;
            padding-top: 15px;
            color: $gray-color;
        }

        .testimonial{
            position: absolute;
            bottom: 5px;

            .name{
                h5,
                span{
                    font-size: .6rem;
                    padding-left: 5px;
                }
            }
            

            .user{
                img{
                    object-fit: contain;
                    width: 50px;
                    border-radius: 50%;
                }
            }
        }
        
    }
}

</style>