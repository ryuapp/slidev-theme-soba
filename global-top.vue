<template>
    <header 
        v-if="$slidev.configs.showPageCount && !$slidev.configs.disablePageCount?.includes($slidev.nav.currentPage)"
        class="absolute top-0 right-0 pt-2 p-5 font-serif text-lg"
    >
        <SlideCurrentNo />
    </header>
</template>