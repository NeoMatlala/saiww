<template>
    <div class="fixed bg-white w-full top-0 z-30">
        <div class="py-5 px-5 md:px-0 border-b border-slate-50">
            <div class="max-w-6xl mx-auto flex justify-between items-center">
                <!-- logo -->
                <div class="w-32 md:w-64 z-40" id="logo" @click="closeMenu()">
                    <NuxtLink to="/">
                        <img src="~/assets/logo.svg" alt="">
                    </NuxtLink>
                </div>

                <!-- desktop nav links -->
                <ul class="hidden md:flex gap-10 text-base capitalize justify-between items-center">
                    <li>
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/#about">About</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/#services">Get Involved</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/#team">Contact Us</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/get-quote" class="border border-1 border-[#383838] capitalize rounded-md px-5 py-2">
                            Attend
                        </NuxtLink>
                    </li>
                </ul>

                <!-- mobile nav links -->
                <div class="md:hidden">
                    <div @click="openMenu()">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- mobile nav -->
        <div class="text-white bg-[#888AD5] fixed top-0 right-0 z-20 h-[100vh] w-full hidden" id="sideNav">
            <div class="absolute top-4 right-5" @click="closeMenu()">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-10 h-10">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                </svg>
            </div>

            <ul class="p-10 mt-36 text-center space-y-10">
                <li class="font-medium text-3xl py-1">
                    <NuxtLink to="/" @click="closeMenu()">Home</NuxtLink>
                </li>
                <li class="font-medium text-3xl py-1">
                    <NuxtLink to="/#about" @click="closeMenu()">About</NuxtLink>
                </li>
                <li class="font-medium text-3xl py-1">
                    <NuxtLink to="/services" @click="closeMenu()">Get Involved</NuxtLink>
                </li>
                <li class="font-medium text-3xl py-1">
                    <NuxtLink to="/#team" @click="closeMenu()">Contact Us</NuxtLink>
                </li>
                <li class="font-medium text-3xl py-1">
                    <NuxtLink to="/get-quote" @click="closeMenu()">Attend</NuxtLink>
                </li>
            </ul>
        </div>
    </div>
</template>


<script>
export default {
    methods: {
        openMenu() {
            const openMenu = document.getElementById("sideNav");

            openMenu.classList.remove("hidden")
            openMenu.classList.add("block")
        },

        closeMenu() {
            const closeMenu = document.getElementById("sideNav");

            closeMenu.classList.remove("block")
            closeMenu.classList.add("hidden")
        },
    }
}
</script>