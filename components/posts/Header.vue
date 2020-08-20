<template>
  <div>
    <b-carousel controls indicators id="silder">
      <div v-for="item in items" :key="item.message">
        <b-carousel-slide
          :caption=item.caption
          :text=item.text
          :img-src=item.image
        ></b-carousel-slide>
      </div>
    </b-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          captions: 'First slide',
          image: require('@/assets/p1.jpg'),
          text: 'Nulla vitae elit libero, a pharetra augue mollis interdum.',
        },
        {
          captions: 'Second slide',
          image: require('@/assets/p2.jpg'),
          text: 'Nulla vitae elit libero, a pharetra augue mollis interdum.',
        },
      ],
    }
  },
}
</script>