<template>
  <b-col md="3">
      <b-card
        :title="title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        class="mb-2 text-center"
      >
        <b-card-text class="text-left">{{content}}</b-card-text>

        <b-button href="#" variant="primary" block>View</b-button>
      </b-card>
    </b-col>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    content: {
      type: String,
      required: false,
    },
  },
}
</script>