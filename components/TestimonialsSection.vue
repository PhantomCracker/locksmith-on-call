<script setup>

const testimonialList = [
    {
        text: 'Locksmith is the only place in town I would call or trust I have never had to wait more than 30 minutes for them to get to any job day or night in any emergency situation I have a home watch business and need to have locks changed or keys made and the guys that come out are so nice and professional.',
        name: 'Mary H.'
    },
    {
        text: 'Thank you for your expert advice on the safe that best fit my needs. I am most happy with the fire and theft test ratings of the American Security Safe. The size and test ratings are perfect for my use. I greatly appreciate the care that Andrew and Austin took with delivering and installing the safe in my home. They were extremely careful and did not scratch the floors or walls.',
        name: 'Susan P.'
    },
    {
        text: 'I want to let you know how pleased we are with the service we received. We have been using your firm for the past eight years and have never been disappointed. Your locksmiths always arrive at the scheduled time and immediately go about their business in a professional and timely manner. I have no reason to use another company.',
        name: 'Dan E.'
    },
    {
        text: 'On time, professional, used drop cloths to protect my carpeting,clear, concise explanation of system. Will highly recommend this firm.',
        name: 'Anita W.'
    },
    {
        text: 'Perfect locksmith on time, stayed until everything was complete, nice guy well done.',
        name: 'Steve S.'
    },
    {
        text: 'You guys are fast, dependable, and always show up on schedule.',
        name: 'Rex W.'
    },
    {
        text: 'Allan arrived promptly, explained what he would do, efficiently performed the work, showed me each of replaced locks, and presented me with his invoice, he was very professional and pleasant.',
        name: 'Jack F.'
    },
    {
        text: 'Amazing service! They care about the customer, very clean and very nice. I really recommend this locksmith.',
        name: 'Jordyn J.'
    },
    {
        text: 'Changed keys and locks for security purposes. They were professional and skilled.',
        name: 'Hugh S.'
    },
    {
        text: 'Arrived on time as promised, was fast and efficient, the work was reasonably priced. I am very satisfied.',
        name: 'Robert W.'
    }
]

</script>

<template>
    <section id="testimonials" aria-label="What our customers are saying" class="bg-slate-50 pt-20 sm:pt-32 testimonials">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <div class="mx-auto max-w-2xl md:text-center">
                <h2 class="font-display pt-4 pb-4 text-3xl tracking-tight text-slate-900 sm:text-4xl mb-6 text-center">Looking For A Highly Recommended Locksmith Service?</h2>
            </div>
            <Swiper
            :modules="[SwiperAutoplay, SwiperEffectCreative]"
            :slides-per-view="1"
            :loop="true"
            :autoplay="{
                delay: 500000,
                disableOnInteraction: true,
            }"
            >
                <SwiperSlide v-for="(testimonial, index) in testimonialList" :key="'testimonial-' + index">
                    <figure class="relative rounded-2xl bg-white p-6 shadow-slate-900/10"><svg aria-hidden="true"
                        width="105" height="78" class="absolute left-6 top-6 fill-slate-100">
                        <path
                        d="M25.086 77.292c-4.821 0-9.115-1.205-12.882-3.616-3.767-2.561-6.78-6.102-9.04-10.622C1.054 58.534 0 53.411 0 47.686c0-5.273.904-10.396 2.712-15.368 1.959-4.972 4.746-9.567 8.362-13.786a59.042 59.042 0 0 1 12.43-11.3C28.325 3.917 33.599 1.507 39.324 0l11.074 13.786c-6.479 2.561-11.677 5.951-15.594 10.17-3.767 4.219-5.65 7.835-5.65 10.848 0 1.356.377 2.863 1.13 4.52.904 1.507 2.637 3.089 5.198 4.746 3.767 2.41 6.328 4.972 7.684 7.684 1.507 2.561 2.26 5.5 2.26 8.814 0 5.123-1.959 9.19-5.876 12.204-3.767 3.013-8.588 4.52-14.464 4.52Zm54.24 0c-4.821 0-9.115-1.205-12.882-3.616-3.767-2.561-6.78-6.102-9.04-10.622-2.11-4.52-3.164-9.643-3.164-15.368 0-5.273.904-10.396 2.712-15.368 1.959-4.972 4.746-9.567 8.362-13.786a59.042 59.042 0 0 1 12.43-11.3C82.565 3.917 87.839 1.507 93.564 0l11.074 13.786c-6.479 2.561-11.677 5.951-15.594 10.17-3.767 4.219-5.65 7.835-5.65 10.848 0 1.356.377 2.863 1.13 4.52.904 1.507 2.637 3.089 5.198 4.746 3.767 2.41 6.328 4.972 7.684 7.684 1.507 2.561 2.26 5.5 2.26 8.814 0 5.123-1.959 9.19-5.876 12.204-3.767 3.013-8.588 4.52-14.464 4.52Z">
                        </path>
                    </svg>
                    <blockquote class="relative">
                        <p class="text-lg tracking-tight text-slate-900">{{ testimonial.text }}</p>
                    </blockquote>
                    <figcaption class="relative mt-6 flex items-center justify-between border-t border-slate-100 pt-6">
                        <div class="font-display text-base text-slate-900">{{ testimonial.name }}</div>
                    </figcaption>
                    </figure>
                </SwiperSlide>
            </Swiper>
        </div>
    </section>
</template>

<style scoped lang="scss">
.testimonials {
    background-color: #ECECEC;
    h2 {
        font-weight: 900;
    }
}

.swiper-slide {
    width: 100px;
    figure {
        padding: 20px;
    }
    p {
        padding-top: 25px;
    }
}
</style>