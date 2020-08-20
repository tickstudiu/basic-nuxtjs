<template>
    <div>
        <Header />
        <PostContent />
    </div>
</template>

<script>
import Header from '@/components/posts/Header';
import PostContent from '@/components/posts/PostContent';

export default {
    layout: "coreLayout",
    components: {
        Header,
        PostContent
    }
}
</script>