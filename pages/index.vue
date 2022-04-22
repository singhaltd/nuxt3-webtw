<script setup>
definePageMeta({
  title: "Some Page",
});
</script>
<template>
  <main>
    <div>
      <figure>
        <img
          src="https://www.kasikornbank.com/SiteCollectionDocuments/personal/img/banner/3000x1000-xpl.jpg"
        />
      </figure>
    </div>
    <div class="w-8/12 mx-auto">
      <div class="grid grid-cols-3 grid-row-2 gap-2">
        <template v-for="i in 5" :key="i">
          <div :class="i == 1 ? 'row-span-2' : ''">
            <div class="card w-full">
              <!-- <figure> -->
              <img
                src="https://www.kasikornbank.com/SiteCollectionDocuments/personal/img/spotlightS/220224-lot1_npa_SpotlightS_mainpage_560x480px.jpg"
                alt="Shoes"
              />
              <!-- </figure> -->
            </div>
          </div>
        </template>
      </div>
    </div>
  </main>
</template>