<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          src: 'https://i.imgur.com/5XCJuJR.png',
        },
        {
          src: 'https://i.imgur.com/w2ybn4S.png',
        },
        {
          src: 'https://i.imgur.com/nGoNQg0.png',
        },
      ],
    }
  },
}
</script>
<style></style>
