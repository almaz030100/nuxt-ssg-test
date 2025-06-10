<template>
  <div style="padding: 30px 10px; border: 1px solid lightgray;">
    <h1>О компании</h1>
    <Splide style="margin-top: 50px; width: 500px">
      <SplideSlide
        v-for="item in sliderItems"
        :key="item"
      >
        <img :src="item" alt="image">
      </SplideSlide>
    </Splide>
  </div>
</template>

<script setup>
const sliderItems = [
  'https://api.kip-group.com/api/main/image/exact/600/99999?imagePath=/upload/iblock/0c0/mn622jwlsf44xp28bnwwervtkcrfv1gg.png',
  'https://api.kip-group.com/api/main/image/exact/600/99999?imagePath=/upload/iblock/de1/3lgo0gi2czqw14h6nqn8tb3xizkw9ply.png',
  'https://api.kip-group.com/api/main/image/exact/600/99999?imagePath=/upload/iblock/445/owsxe4prlj9v264ar0ar3jx5r0t6amvt.png',
]
</script>

<style lang="scss" scoped>

</style>