<template>
    <div>
        <!-- hero section -->
        <div class="hidden md:block w-full h-48 md:h-[50vh]">
            <!-- <img src="~/assets/contact-us-hero.jpg" class="w-full object-cover h-full" alt=""> -->
        </div>

        <!-- forms -->
        <section class="max-w-6xl mx-auto md:mt-10">
            <div class="flex flex-col md:flex-row items-start justify-between gap-7">
                <div class="w-full bg-white md:w-1/2 md:p-10 md:-mt-40 ">
                    <small class="text-[#7E69AD] mb-3">Contact Us</small>
                    <h1 class="mb-5 md:mb-10 font-medium text-4xl md:text-6xl leading-tight text-[#383838]">Get a quote</h1>
                    <p>
                        Please complete the below form to get a quote from us and we'll make sure the right team member gets back to you.
                    </p>

                    <div class="mt-16 space-y-5 text-sm hidden md:block">
                        <p class="flex justify-start items-center gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-[#383838]">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                                </svg>
                            </span>
                            075 415 4123
                        </p>
                        <p class="flex justify-start items-center gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-[#383838]">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                                </svg>
                            </span>
                            065 458 7411
                        </p>
                        <p class="flex justify-start items-center gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-[#383838]">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                                </svg>
                            </span>
                            hello@solvyng.io
                        </p>
                        <p class="flex justify-start items-start gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                                </svg>
                            </span>
                            Spaces, Atrium on 5th Building, 9th Floor <br>5th Street,<br>Sandton,<br>Johannesburg,<br>2196
                        </p>
                    </div>
                </div>

                <div class="w-full mt-5 md:mt-0 space-y-5 md:w-1/2 md:p-5">
                    <div>
                        <label for="email">Email *</label> <br>
                        <input id="email" type="text" class="mt-2 border w-full p-1">
                    </div>
                    <div class="flex flex-col md:flex-row space-y-5 md:space-y-0 gap-x-5 justify-between items-center">
                        <div class=" w-full">
                            <label for="name">Name *</label> <br>
                            <input id="name" type="text" class="mt-2 border w-full p-1">
                        </div>
                        <div class="w-full">
                            <label for="surname">Surname *</label> <br>
                            <input id="surname" type="text" class="mt-2 border w-full p-1">
                        </div>
                    </div>
                    <div>
                        <label for="message">Message *</label> <br>
                        <textarea name="" id="message" rows="5" class="mt-2 border w-full p-3"></textarea>
                    </div>
                    <button class="bg-[#383838] uppercase text-white px-5 py-2">Submit</button>

                    <div class="pt-8 space-y-5 text-sm md:hidden">
                        <p class="flex justify-start items-center gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-[#383838]">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                                </svg>
                            </span>
                            075 415 4123
                        </p>
                        <p class="flex justify-start items-center gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-[#383838]">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                                </svg>
                            </span>
                            065 458 7411
                        </p>
                        <p class="flex justify-start items-center gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 stroke-[#383838]">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                                </svg>
                            </span>
                            hello@solvyng.io
                        </p>
                        <p class="flex justify-start items-start gap-x-5">
                            <span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                                </svg>
                            </span>
                            Spaces, Atrium on 5th Building, 9th Floor <br>5th Street,<br>Sandton,<br>Johannesburg,<br>2196
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

