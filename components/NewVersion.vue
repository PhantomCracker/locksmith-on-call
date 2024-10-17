<script setup></script>

<template>
    <div class="container-fluid p-0">
        <div class="row navigation pt-3 pb-3">
            <div class="col-12 col-md-6 text-align-center">
                <NuxtLink to="/">
                    <img src="@/assets/logo.webp" class="logo" alt="logo" />
                </NuxtLink>
            </div>
            <div class="col-12 col-md-6 pt-4 pt-md-0 d-flex align-items-center justify-content-end">
                <a href="tel:01173256595" class="float-phone d-flex">
                    <Icon name="ph:phone-call" class="fa-phone " />
                    <div class="phone-text ps-3">
                        Call 24/7 Emergency Service
                        <span class="phone-number">0117 325 6595</span>
                    </div>
                </a>
            </div>
        </div>
        <div class="row hero pt-5">
            <div class="row text-align-center hero-div-one">
                <div class="col-12 col-md-8 p-5 ps-8">
                    <h1>EMERGENCY LOCKSMITHS, CALL 24/7</h1>
                    <h2 class="pt-3">Fast Emergency Locksmiths Near You.</h2>
                    <h2 class="pt-3">Service on spot within 20 minutes</h2>
                    <a href="tel:01173256595"><button class="call-now mt-5 p-2 mb-5">
                        CALL NOW <br> 0117 325 6595
                    </button></a>
                </div>
            </div>
            <div class="row services pt-4 pb-3">
                <div class="col-12 col-md-3 d-flex justify-content-center align-items-center service">
                    <Icon name="mdi:truck-fast-outline" class="truck-icon" />
                    <div class="service-text">
                        <h3>Fast response</h3>
                        <p>We arrive in 20 minutes</p>
                    </div>
                </div>
                <div class="col-12 col-md-3 d-flex justify-content-center align-items-center service">
                    <Icon name="material-symbols-light:editor-choice-outline-rounded" class="best-choice-icon" />
                    <div class="service-text">
                        <h3>Best Choice Guarantee</h3>
                        <p>CRB/DBS Checked</p>
                    </div>
                </div>
                <div class="col-12 col-md-3 d-flex justify-content-center align-items-center service">
                    <Icon name="hugeicons:location-05" class="location-icon" />
                    <div class="service-text">
                        <h3>No Call Out Fee</h3>
                        <p>No Charge To Come</p>
                    </div>
                </div>
                <div class="col-12 col-md-3 d-flex justify-content-center align-items-center service">
                    <Icon name="simple-icons:leaderprice" class="best-price-icon" />
                    <div class="service-text">
                        <h3>Best Prices</h3>
                        <p>Affordable Rates</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row services-cards pt-3">
            <div class="col-6 col-md-3 card-background">
                <div class="card-1">
                    <h4>Emergency locksmith</h4>
                </div>
            </div>
            <div class="col-6 col-md-3 card-background">
                <div class="card-2">
                    <h4>Lock change</h4>
                </div>
            </div>
            <div class="col-6 col-md-3 card-background">
                <div class="card-3">
                    <h4>Burglary Repair</h4>
                </div>
            </div>
            <div class="col-6 col-md-3 card-background">
                <div class="card-4">
                    <h4>Residential / Comercial</h4>
                </div>
            </div>
        </div>
    </div>
    <hr>
    <div class="row information mb-5">
        <div class="col-12 col-md-8">
            <h5 class="pt-3 pb-3">Cheap locksmith near me available 24/7</h5>
            <p class="pt-3 pb-3">We provide the best quality locksmith services with multiple teams located near you, our services include business locksmith services, emergency locksmith services, 24-hour locksmith services, with us you’ll receive trusted locksmith services in the most urgent of manner.</p>
            <ul class="p-0">
                <li>100% Satisfaction Guarantee</li>
                <li>Local Locksmiths</li>
                <li>Mobile service, we come to you</li>
                <li>Licensed & insured professionals.</li>
                <li>24/7 availability, for your peace of mind</li>
                <li>Fast & efficient</li>
                <li>Trustworthy</li>
                <li>Reliable & Secure</li>
                <li>Quick & Convenient</li>
                <li>Local expertise</li>
                <li>Satisfaction guarantee</li>
                <li class="pb-2">Expert security consultationse</li>
            </ul>
            <a href="tel:01173256595"><button class="call-now p-2">
                CALL NOW 0117 325 6595
            </button></a>
        </div>
    </div>
    <InfoSection />
    <TrustedSection />
    <TestimonialsSection />
    <div class="row footer">
        <div class="col-12 col-md-6">
            <NuxtLink to="/">
                <img src="@/assets/logo.webp" class="logo" alt="logo" />
            </NuxtLink>
            <a href="tel:01173256595"><button class="call-now p-2">
                CALL NOW 0117 325 6595
            </button></a>
            <p>© 2024 Locksmith 4 All. All Rights Reserved.</p>
        </div>
        <div class="col-12 col-md-6">
            <NuxtImg src="/images/badges/247-service-badge.webp" class="service-badge" alt="badge1"/>
            <h6>BUSINESS HOURS</h6>
            <p>Our support available to help you 24 hours a day, seven days a week.</p>
            <ul>
                <li>OPEN 24h</li>
                <li>7 DAYS a WEEK</li>
            </ul>
        </div>
    </div>
    <div class="row">
        <div class="col-12">
            <a href="tel:01173256595"><button class="phone-call p-2">
                CALL NOW 0117 325 6595
            </button></a>
        </div>
    </div>
</template>

<style scoped lang="scss">
.navigation {
  padding: 0;
  margin: 0;
  background: #000;

  .float-phone {
    text-decoration: none;
    color: #FE5B5C;
    float: right;
  }

  .phone-text {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 1.3rem;
    color: #fff;
    font-weight: 600;
  }

  .phone-number {
    font-size: 2rem;
    color: #FE5B5C;
  }
}

.fa-phone {
    width: 70px;
    height: 70px;
    background: #000;
    border-radius: 50px;
    padding: 12px;
    border: 2px solid #FE5B5C;
}

.hero {
    background-image: url("@/assets/images/hero-background.webp");
    background-size: cover;
    background-repeat: no-repeat;

    h1, h2 {
        color: #fff;
    }

    .call-now {
        color: #fff;
        background-color: #FE5B5C;
        width: 150px;
        border-radius: 15px;
    }

    .services {
        background-color: rgba(179,0,0, 0.5);

        .truck-icon, .best-choice-icon, .location-icon, .best-price-icon {
            width: 70px;
            height: 70px;
            color: #FE5B5C;
            padding-right: 10px;
        }
        .service-text {
            color: #fff;
            h3 {
                font-size: 1rem;
            }
            p {
                font-size: 0.8rem;
            }
        }
    }
}

.services-cards {
    position: relative;
    display: flex;
    justify-content: center;

    .card-background {
        background-color: #ECECEC;
        width: 212px;
        height: 200px;
        padding: 0;
        border-right: 10px solid #fff;
        margin-right: 30px;
    }
    h4 {
        background-color: #FE5B5C;
        color: #fff;
        font-size: 0.9rem;
        position: absolute;
        bottom: 10px;
        margin: 0;
        width: 200px;
        text-align: center;
        padding: 10px;
    }
    .card-1 {
        background-image: url('@/assets/images/services/service1.webp');
        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 50%;
        width: 200px;
        height: 200px;
    }
    .card-2 {
        background-image: url('@/assets/images/services/service2.webp');
        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 50%;
        width: 200px;
        height: 200px;
    }
    .card-3 {
        background-image: url('@/assets/images/services/service3.webp');
        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 50%;
        width: 200px;
        height: 200px;
    }
    .card-4 {
        background-image: url('@/assets/images/services/service4.webp');
        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 50%;
        width: 200px;
        height: 200px;
    }
}
.information {
    color: gray;
    justify-content: center;

    a {
        text-decoration: none;
        .call-now {
            font-weight: 600;
            color: #fff;
        }
    }

    h5 {
        color: #000;
        font-size: 1.5rem;
        font-weight: 700;
        text-align: center;
    }
    p {
        text-align: center;
    }
    ul {
        list-style: none;
        li {
            font-weight: 600;
        }
    }
    ul li:before {
        content: '✓';
        color: #FE5B5C;
        padding-right: 10px;
    }
    .call-now {
        color: #000;
        background-color: #FE5B5C;
        width: 300px;
        border-radius: 15px;
        display: flex;
        justify-content: center;
        margin: 0 auto;
    }
}
.footer {
    background-color: rgba(254,91,92, 0.8);
    padding: 2rem;

    p, li {
        color: #fff;
    }
    h6 {
        color: #fff;
        font-weight: 600;
    }
    .call-now {
        color: #000;
        background-color: #FE5B5C;
        width: 300px;
        border-radius: 15px;
        display: flex;
        justify-content: center;
        margin: 0 auto;
        margin-top: 15px;
        margin-bottom: 15px;
    }
    .service-badge {
        width: 150px;
        padding-top: 15px;
        padding-bottom: 15px;
    }
}
.phone-call {
    display: none; 
    position: fixed;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    background-color: #FE5B5C;
    color: #000;
    padding: 15px 30px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 15px;
    font-weight: 700;
}

@media only screen and (max-width: 600px) {
    .logo {
        width: 80%;
    }
    .text-align-center {
        text-align: center;
    }
    .hero {
        background-image: url("@/assets/images/header-man.webp");
        background-size: contain;
        background-position: top;
        background-color: #000;
        .text-align-center {
            padding: 15px;
        }
        .hero-div-one {
            padding-right: 0;
            :first-child {
                h1, h2 {
                    font-weight: 600;
                    font-size: 1.6rem;
                }
            }
        }
        h1 {
            padding-bottom: 15px;
        }
        h2 {
            font-weight: 400 !important;
            font-size: 1.2rem !important;
            padding-top: 0 !important;
        }
        > div > div {
            padding-top: 0 !important;
        }
        button {
            margin-top: 10px !important;
        }
    }
    .services {
        margin-top: -90px;
        padding-left: 0;
        padding-right: 0;
        .service {
            padding-left: 120px;
            justify-content: unset !important;
        }
    }
    .services-cards {
        .card-background {
            margin-right: 0;
            width: 190px;
            margin-top: 10px;
            .card-1, .card-2, .card-3, .card-4 {
                width: 180px;
            }
        }
        h4 {
            width: 180px;
        }
    }
    .card-background {
        h4 {
            background-color: #FE5B5C;
            color: #fff;
            font-size: 0.9rem;
            position: relative;
            text-align: center;
            padding: 10px;
            top: 95%;
            transform: translateY(-100%);
        }
    }
    .information {
        text-align: center;
    }
    .footer {
        text-align: center;
        a {
            text-decoration: none;
            .call-now {
                font-weight: 600;
                color: #fff;
            }
        }
        ul {
            list-style: none;
            padding-left: 0;
        }
    }
    .phone-call {
        display: block;
        color: #000;
        background-color: #F7CE1F;
        width: 300px;
        border-radius: 15px;
        display: flex;
        justify-content: center;
        margin: 0 auto;
        z-index: 30;
    }
    .fa-phone {
        display: none;
    }
    .float-phone {
        margin: 0 auto;
    }
}
</style>