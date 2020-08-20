<template>
    <b-container fluid class="px-0">
        <Header />
        <b-row>
            <b-col>
                <PostContent />
            </b-col>
            <b-col>
                <PostContent />
            </b-col>
            <b-col>
                <PostContent />
            </b-col>
        </b-row>
    </b-container>
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