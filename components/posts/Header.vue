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
          image: 'https://picsum.photos/1024/480/?image=52',
          text: 'Nulla vitae elit libero, a pharetra augue mollis interdum.',
        },
        {
          captions: 'Second slide',
          image: 'https://picsum.photos/1024/480/?image=58',
          text: 'Nulla vitae elit libero, a pharetra augue mollis interdum.',
        },
      ],
    }
  },
}
</script>