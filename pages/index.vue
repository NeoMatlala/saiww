<template>
    <div class="text-[#383838] relative">
        <!-- hero -->
        <section class="max-w-6xl mx-auto relative z-20 pb-10">
            <div class="mt-5 md:mt-20">
                <small>
                    <div class="flex justify-start items-center mt-5 gap-x-4 font-normal text-sm">
                        <div class="flex justify-start items-center gap-x-2">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 stroke-[#E44700]">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 012.25-2.25h13.5A2.25 2.25 0 0121 7.5v11.25m-18 0A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75m-18 0v-7.5A2.25 2.25 0 015.25 9h13.5A2.25 2.25 0 0121 11.25v7.5m-9-6h.008v.008H12v-.008zM12 15h.008v.008H12V15zm0 2.25h.008v.008H12v-.008zM9.75 15h.008v.008H9.75V15zm0 2.25h.008v.008H9.75v-.008zM7.5 15h.008v.008H7.5V15zm0 2.25h.008v.008H7.5v-.008zm6.75-4.5h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V15zm0 2.25h.008v.008h-.008v-.008zm2.25-4.5h.008v.008H16.5v-.008zm0 2.25h.008v.008H16.5V15z" />
                            </svg>
                            <span>July 21-23, 2024</span>
                        </div>
                        
                        <span>
                            <svg xmlns="http://www.w3.org/2000/svg" width="6" height="6" fill="currentColor" class="bi bi-circle-fill" viewBox="0 0 16 16">
                                <circle cx="8" cy="8" r="8"/>
                            </svg>
                        </span>
                        <div class="flex justify-start items-center gap-x-2">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 stroke-[#E44700]">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                            </svg>
                            <span>Sandton Convention Center, Johannesburg</span>
                        </div>
                        
                    </div>
                </small>
                <h1 class="text-3xl md:text-7xl mb-5 mt-3 text-[#383838] font-bold">
                    South Africa International Water Week 2024
                </h1>

                <p class="text-xl w-1/2 leading-9">
                    Developing solutions to the various water-related challenges facing our country 
                </p>
                
                <div class="mt-10">
                    <nuxtLink to="/articles" class="flex gap-x-3 bg-[#009DE4] text-white px-16 py-5 w-fit rounded-md items-center justify-center">Register for free
                        <span>
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-3 h-3 stroke-2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25" />
                            </svg>
                        </span>
                    </nuxtLink>
                </div>
            </div>
        </section>

        <!-- about -->
        <section id="about" class="md:pt-20 my-8 max-w-6xl mx-auto">
            <div class="w-full h-[80vh] z-10 relative">
                <div class="relative mix-blend-darken w-11/12">
                    <img src="~/assets/about.jpg" alt="BannerImage" class="absolute h-[70vh] lg:h-[80vh] w-11/12 object-cover object-right opacity-30 " />
                    <div class="absolute -z-10 bg-gradient-to-r from-black to-black h-[70vh] lg:h-[80vh] w-11/12" />
                </div>

                <div class="bg-[#FAFAFA] p-10 absolute w-2/3 -top-10 right-0">
                    <h1 class="text-3xl md:text-5xl mb-8 mt-3 text-[#383838] font-medium">SAIWW is more than just a conference ...</h1>

                    <p class="text-lg leading-9">
                        The South Africa International Water Week (SAIWW) is thee conference for discussing the various water issues, attracting a diverse mix of participants from many professional backgrounds and every corner of the African continent. Together we develop solutions to water-related challenges and the climate crisis.  
                    </p>
                    
                    <div class="mt-10">
                        <nuxtLink to="/articles" class="flex gap-x-3 bg-[#009DE4] text-white px-16 py-5 w-fit rounded-md items-center justify-center">Register for free
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-3 h-3 stroke-2">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25" />
                                </svg>
                            </span>
                        </nuxtLink>
                    </div>
                </div>
            </div>
        </section>

        <!-- speakers -->
        <section class="my-10 md:my-0 pt-4 max-w-6xl mx-auto" id="team">
            <hr class="w-36 mb-8 border-1 mx-auto rounded-lg border-[#333]">
            <h1 class="text-center mb-10 mt-5 text-4xl md:text-5xl font-medium">SAIWW 2024 Speakers</h1>

            <div class="mt-10 flex justify-between items-center gap-1">
                <div class="p-2 w-1/3 relative">
                    <div class="h-96 w-full">
                        <img src="../assets/headshot1.jpg" class="w-full h-full object-cover" alt="">
                    </div>
                    <div class="bg-white absolute bottom-5 py-2 left-8 text-center rounded-md w-5/6">
                        <h4 class="font-medium text-xl">Thulasizwe Mavuso</h4>
                        <p class="font-thin text-sm">Managing Director: Perfect Water</p>
                    </div>
                </div>
                <div class="p-2 w-1/3 relative">
                    <div class="h-96 w-full">
                        <img src="../assets/headshot2.jpg" class="w-full h-full object-cover" alt="">
                    </div>
                    <div class="bg-white absolute bottom-5 py-2 left-8 text-center rounded-md w-5/6">
                        <h4 class="font-medium text-xl">Thobekani Ndlovu</h4>
                        <p class="font-thin text-sm">COO: Meetsi Solution</p>
                    </div>
                </div>
                <div class="p-2 w-1/3 relative">
                    <div class="h-96 w-full">
                        <img src="../assets/headshot3.jpg" class="w-full h-full object-cover" alt="">
                    </div>
                    <div class="bg-white absolute bottom-5 py-2 left-8 text-center rounded-md w-5/6">
                        <h4 class="font-medium text-xl">Bethuel Mhlongo</h4>
                        <p class="font-thin text-sm">Founder: Wattrix Civil Works</p>
                    </div>
                </div>
            </div>
        </section>

        
        <!-- chairman word -->
        <section class="mt-16 py-16 bg-[#009DE4]" id="testimonial">
            <div class="max-w-6xl mx-auto text-white">
                <h1 class="text-center font-medium text-4xl px-5 md:px-0">A word from the chairman ...</h1>

                <div class="flex flex-col md:flex-row justify-between gap-10 items-center mt-16 px-5 md:px-20">
                    <div class="w-full md:w-1/2 rounded-tr-[80px] h-60 md:h-[450px]" id="testimonial-img"></div>
                    <div class="w-full md:w-1/2 md:h-[400px] relative">
                        <span class="text-9xl font-bold text-[#F18B77]" id="apostrophe">"</span>
                        <p class="italic -mt-10 text-base md:text-base font-thin">
                            The biggest problems we face today frequently begin with water. You can meet a wide range of influential decision-makers, business executives, urban planners, activists, and researchers from all around the world at the South Africa International Water Week(SAIWW). Many are trailblazers who have discovered fresh, clever methods of managing water. People attend the conference to exchange fresh concepts, gain knowledge from one another, and work together on cutting-edge solutions.
                        </p>
                        <span class="text-9xl absolute bottom-2 right-0 font-bold text-[#F18B77]" id="apostrophe">"</span>
                        <h4 class="font-semibold text-xl mt-8">Walter Mokoena</h4>
                        <p class="font-thin text-sm">Chairman -  SAIWW</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- why partner? -->
        <section class="py-2 max-w-6xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between gap-16 items-center mt-16 px-5 md:px-0">
                <div class="w-1/2">
                    <h1 class="font-medium text-4xl md:px-0 mb-5">Why Partner with SAIWW ?</h1>
                    <div class="w-full h-80 mb-6">
                        <img src="~/assets/why-attend.jpg" class="w-full object-cover h-full">
                    </div>
                    <p class="leading-8">
                        Be part of the change and embrace of the South Africa International Water Week (SAIWW), embracing the current vision of SAIWW to encourage change and positive disruption. SAIWW will bring together industry experts, future leaders and visionaries paving the path for our water industry.
                    </p>
                </div>
                <div class="w-1/2">
                    <h1 class="font-medium text-4xl md:px-0 mb-5">Attend SAIWW</h1>
                    <div class="w-full h-80 mb-6">
                        <img src="~/assets/why-sponsor.jpg" class="w-full object-cover h-full">
                    </div>
                    <p class="leading-8">
                        Build your pipeline for 2024 and beyond by joining SAIWW. Utilize the platform provided by the South Africa International Water Week to get your customized possibilities in front of the most significant C-suite executives, investors, and decision-makers.
                    </p>
                </div>
            </div>
        </section>
        

        <!-- partners -->
        <section id="services" class="mt-16 max-w-6xl mx-auto">
            <hr class="w-36 mb-8 border-1 mx-auto rounded-lg border-[#333]">
            <h1 class="text-center mb-10 mt-5 text-4xl md:text-5xl font-medium">Partners & Sponsors</h1>
            
            <div class="w-full mt-10 flex item-center justify-between">
                <img src="~/assets/DWS-logo.png" class=" w-10 object-contain md:w-80">
                <img src="~/assets/sab.png" class="w-10 md:w-40 object-contain">
                <img src="~/assets/jp.png" class="w-10 md:w-32 md:h-32">
                <img src="~/assets/msb-dark.png" class="w-10 md:w-32">
            </div>
            <div class="w-full flex item-center mt-8 justify-center gap-x-24">
                <img src="~/assets/econvert.png" class="w-10 object-contain md:w-96">
                <img src="~/assets/aquamat-logo.png" class="w-10 object-contain md:w-80">
            </div>
        </section>
        
        <!-- hero image -->
        <div class="w-[50vw] h-[80vh] absolute top-0 right-0 z-10 ">
            <div class="relative mix-blend-overlay">
                <img src="~/assets/hero.jpg" alt="BannerImage" class="absolute h-[70vh] lg:h-[80vh] w-full object-cover object-right opacity-30 " />
                <div class="absolute -z-10 bg-gradient-to-r from-[#CDCDCD]  to-black h-[70vh] lg:h-[80vh] w-full" />
            </div>
        </div>
    </div>
</template>

<style>
    #testimonial-img {
        background: url('assets/walter.jpg') no-repeat center;
        background-size: cover;
    }

    
</style>