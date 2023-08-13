<template>
    <div>
        <div class="grid grid-cols-4 gap-5 gap-y-10">
            <div v-for="(p, index) in result" v-bind:key="index" >
                <NuxtLink :to="`/articles/${index}`">
                    <div class="border border-1 border-black p-2">
                        <div class="h-40 mb-3">
                            <img :src="`${p.urlToImage}`" alt="" class="w-full h-full object-cover">
                        </div>
                        
                        <h1 class="font-medium multiline-ellipsis w-full">{{ p.title }}</h1>
                    </div>
                    
                </NuxtLink>
            </div>
        </div>
    </div>
</template>

<script setup>

    // fetch articles
    const api_key = '81e8c5c63cbd4223aa862f3fcbe5eac2';
    const article_count = 4;

    const { data: articles } = await useFetch(`https://newsapi.org/v2/everything?domains=techcrunch.com,thenextweb.com&pageSize=${article_count}&apiKey=${api_key}`)

    const result = articles.value.articles

    //console.log(result)
  
</script>
  

<style>
    .multiline-ellipsis {
        overflow: hidden;
        display: -webkit-box;
        -webkit-box-orient: vertical;
        -webkit-line-clamp: 2; /* start showing ellipsis when 3rd line is reached */
        white-space: pre-wrap; /* let the text wrap preserving spaces */
    }
</style>