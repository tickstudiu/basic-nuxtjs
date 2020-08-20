<template>
    <div>
        <Header />
        <h2>Hello Post Page</h2>
    </div>
</template>

<script>
import Header from '@/components/posts/Header';

export default {
    layout: "coreLayout",
    components: {
        Header,
    }
}
</script>