<template>
  <b-container fluid class="px-0">
    <Header />
    <b-row>
      <PostContent
          title="Title1"
          content="Some quick example text to build on the card title and make up the bulk of the card's content."
        />
      <PostContent
          title="Title2"
          content="Some quick example text to build on the card title and make up the bulk of the card's content."
        />
      <PostContent
          title="Title3"
          content="Some quick example text to build on the card title and make up the bulk of the card's content."
        />
        <PostContent
          title="Title3"
          content="Some quick example text to build on the card title and make up the bulk of the card's content."
        />
        <PostContent
          title="Title3"
          content="Some quick example text to build on the card title and make up the bulk of the card's content."
        />
    </b-row>
  </b-container>
</template>

<script>
import Header from '@/components/posts/Header'
import PostContent from '@/components/posts/PostContent'

export default {
  layout: 'coreLayout',
  components: {
    Header,
    PostContent,
  },
}
</script>