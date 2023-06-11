<template>
    <div class="slidev-layout profile">
      <div class="my-auto w-full grid grid-cols-2">
        <div>
            <slot />
        </div>
        <div class="m-12">
            <img 
                class="rounded-full aspect-square w-full my-auto" 
                :src="$attrs.profileImage || '/soba.jpg'"
            />
        </div>
      </div>
    </div>
</template>