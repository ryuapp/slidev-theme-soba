<template>
  <div class="slidev-layout profile">
    <div class="my-auto grid w-full grid-cols-2">
      <div>
        <slot />
      </div>
      <div class="m-12">
        <img
          class="my-auto aspect-square w-full rounded-full"
          :src="$attrs.profileImage || '/soba.jpg'"
        />
      </div>
    </div>
  </div>
</template>
