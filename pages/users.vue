<template>
    <div>
        <h2>Form Users</h2>
        <form>
            <input type="text"/>
            <input type="submit" value="insert"/>
        </form>
        <nuxt-child/>
    </div>
</template>

<script>
export default {
    layout: "coreLayout",
    components: {}
}
</script>