<template>
  <div>
    <b-carousel controls indicators id="silder">
      <!-- Text slides with image -->
      <b-carousel-slide
        caption="First slide"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
        img-src="https://picsum.photos/1024/480/?image=52"
      ></b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide
        caption="Second slide"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
        img-src="https://picsum.photos/1024/480/?image=58"
      ></b-carousel-slide>

      <!-- Slides with img slot -->
      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
      <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block img-fluid w-100"
            caption="Thrid slide"
            text="Nulla vitae elit libero, a pharetra augue mollis interdum."
            src="https://picsum.photos/1024/480/?image=55"
          />
        </template>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>