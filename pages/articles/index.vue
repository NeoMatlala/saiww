<template>
    <div class="text-[#383838]">
        <!-- hero -->
        <section class="max-w-6xl mx-auto relative pb-10">
            <h1 class="font-medium text-4xl md:text-6xl mt-5 md:mt-10 leading-tight mb-10">Our Articles</h1>
            
            <hr class="w-14 md:w-40 border-2 rounded-lg border-[#7E69AD] absolute top-6 md:top-10 md:left-1/3 right-10 md:right-40">
        </section>

        <section class="max-w-6xl mx-auto relative pb-10">
            <div class="grid grid-cols-4 gap-5 gap-y-10">
                <div v-for="p in result" v-bind:key="p.source.id" class="border border-1 border-black p-2">
                    <div class="h-40 mb-3">
                        <img :src="`${p.urlToImage}`" alt="" class="w-full h-full object-cover">
                    </div>
                    
                    <h1 class="font-medium multiline-ellipsis w-full">{{ p.title }}</h1>
                </div>
            </div>
        </section>
        
    </div>
</template>

<script setup>

    // fetch articles
    const api_key = '81e8c5c63cbd4223aa862f3fcbe5eac2';

    const { data: articles } = await useFetch(`https://newsapi.org/v2/everything?domains=techcrunch.com,thenextweb.com&apiKey=${api_key}`)

    const result = articles.value.articles

    console.log(result)
  
</script>