<template>
    <div class="text-[#383838]">
        <!-- hero -->
        <section class="max-w-6xl mx-auto relative mt-5">
            <NuxtLink class="flex items-center justify-start gap-x-2" to="/#article">
                <span>
                    <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" fill="currentColor" class="bi bi-chevron-left" viewBox="0 0 16 16">
                      <path fill-rule="evenodd" d="M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z"/>
                    </svg>
                </span>
                <span class="text-sm">Back</span>
            </NuxtLink>
            <p class="text-[#888AD5] text-sm mt-10 mb-2">Article</p>
            <h1 class="font-medium text-4xl md:text-6xl mb-6">{{result.title}}</h1>

            <p class="text-xl font-normal">{{ result.description }}</p>

            <div class="flex justify-start items-center mt-5 gap-x-5 font-normal text-sm">
                <span>{{ result.author }}</span>
                <span>
                    <svg xmlns="http://www.w3.org/2000/svg" width="6" height="6" fill="currentColor" class="bi bi-circle-fill" viewBox="0 0 16 16">
                        <circle cx="8" cy="8" r="8"/>
                    </svg>
                </span> 
                <span>{{ result.publishedAt }}</span>
            </div>

            <div class="w-full md:h-[600px] bg-red-400 mt-10">
                <img :src="`${result.urlToImage}`" alt="" class="w-full h-full object-cover">
            </div>

            <div class="mt-10">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores omnis eos, velit placeat, laboriosam dolores repudiandae dolor eligendi soluta vero officiis magni odio excepturi nam maxime sunt provident tempore eveniet ducimus, sint ipsa? Tenetur facilis cupiditate incidunt ea nihil enim, accusamus molestiae fugiat id hic labore, corporis distinctio quia. Voluptas molestias veniam vel doloribus, officia mollitia. Provident quas exercitationem dicta hic placeat, consectetur voluptates et quis itaque tempora voluptas expedita, ipsa quod, sint obcaecati accusamus eius possimus. Beatae, provident dicta, laudantium possimus molestiae ipsa asperiores nesciunt magnam unde atque ab consectetur, tempore ipsam officiis dolorem! Consectetur sunt tempore molestiae sit laudantium suscipit. Fuga odio voluptates nisi dolores, voluptatibus vel similique ad distinctio nulla est itaque enim. <br><br> Autem molestias cumque cum dolore, veniam asperiores laboriosam sint! Consequatur iste commodi eveniet tenetur provident animi optio voluptatibus exercitationem architecto. Dolore nam tempora quaerat culpa officiis, esse delectus fuga explicabo sapiente saepe laudantium, qui asperiores nobis debitis unde accusantium aliquid minus doloribus officia magni consectetur, pariatur corrupti ab? Deleniti mollitia eligendi nulla aspernatur, doloremque harum facilis maiores possimus repellendus perspiciatis sint autem excepturi exercitationem non dolorem ipsam neque, aliquam nobis. Cum ipsa libero atque, facere quo odit maxime optio dolorum ratione quidem assumenda sit. Distinctio labore harum incidunt, voluptates voluptatem blanditiis sapiente amet iusto, ipsum quasi id voluptatibus autem. Ducimus quasi maxime architecto soluta, obcaecati laborum voluptates blanditiis animi quod consequuntur repellendus, quisquam distinctio velit quos ea quae laudantium natus nihil! Assumenda optio sapiente illo magnam. Officiis dolorum maxime adipisci, cupiditate sapiente ea et nihil provident consequuntur deserunt iusto tempore modi praesentium sit suscipit aperiam rem excepturi! Eius rem illum molestiae, non aspernatur facilis recusandae cum omnis aperiam eligendi cupiditate impedit voluptates beatae quibusdam explicabo saepe rerum. Quaerat laudantium beatae perferendis ducimus aspernatur corporis, fugiat odit ipsam dolorem, fugit voluptatum suscipit necessitatibus aliquid assumenda.<br><br>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores omnis eos, velit placeat, laboriosam dolores repudiandae dolor eligendi soluta vero officiis magni odio excepturi nam maxime sunt provident tempore eveniet ducimus, sint ipsa? Tenetur facilis cupiditate incidunt ea nihil enim, accusamus molestiae fugiat id hic labore, corporis distinctio quia. Voluptas molestias veniam vel doloribus, officia mollitia. Provident quas exercitationem dicta hic placeat, consectetur voluptates et quis itaque tempora voluptas expedita, ipsa quod, sint obcaecati accusamus eius possimus. Beatae, provident dicta, laudantium possimus molestiae ipsa asperiores nesciunt magnam unde atque ab consectetur, tempore ipsam officiis dolorem! Consectetur sunt tempore molestiae sit laudantium suscipit. Fuga odio voluptates nisi dolores, voluptatibus vel similique ad distinctio nulla est itaque enim. <br><br> Autem molestias cumque cum dolore, veniam asperiores laboriosam sint! Consequatur iste commodi eveniet tenetur provident animi optio voluptatibus exercitationem architecto. Dolore nam tempora quaerat culpa officiis, esse delectus fuga explicabo sapiente saepe laudantium, qui asperiores nobis debitis unde accusantium aliquid minus doloribus officia magni consectetur, pariatur corrupti ab? Deleniti mollitia eligendi nulla aspernatur, doloremque harum facilis maiores possimus repellendus perspiciatis sint autem excepturi exercitationem non dolorem ipsam neque, aliquam nobis. Cum ipsa libero atque, facere quo odit maxime optio dolorum ratione quidem assumenda sit. Distinctio labore harum incidunt, voluptates voluptatem blanditiis sapiente amet iusto, ipsum quasi id voluptatibus autem. Ducimus quasi maxime architecto soluta, obcaecati laborum voluptates blanditiis animi quod consequuntur repellendus, quisquam distinctio velit quos ea quae laudantium natus nihil! Assumenda optio sapiente illo magnam. Officiis dolorum maxime adipisci, cupiditate sapiente ea et nihil provident consequuntur deserunt iusto tempore modi praesentium sit suscipit aperiam rem excepturi! Eius rem illum molestiae, non aspernatur facilis recusandae cum omnis aperiam eligendi cupiditate impedit voluptates beatae quibusdam explicabo saepe rerum. Quaerat laudantium beatae perferendis ducimus aspernatur corporis, fugiat odit ipsam dolorem, fugit voluptatum suscipit necessitatibus aliquid assumenda.
                </p>
            </div>
        </section>
    </div>
</template>

<script setup>

    const { id } = useRoute().params;
    const api_key = '81e8c5c63cbd4223aa862f3fcbe5eac2';
    const url = `https://newsapi.org/v2/everything?domains=techcrunch.com,thenextweb.com&apiKey=${api_key}`;

    //fetch article
    const { data: article } = await useFetch(`https://newsapi.org/v2/everything?domains=techcrunch.com,thenextweb.com&apiKey=${api_key}`)

    const result = article.value.articles[id]
</script>
