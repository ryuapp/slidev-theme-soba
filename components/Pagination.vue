<template>
  <div
    v-if="$slidev.configs.showPageCount && !$slidev.configs.disablePageCount?.includes($slidev.nav.currentPage)"
    class="font-serif text-lg"
  >
    <SlideCurrentNo />
  </div>
</template>
