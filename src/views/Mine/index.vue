<template>
    <div id="main">
        <Header title="我的喵喵"></Header>
        <login></login>
        <TabBar></TabBar>
    </div>
</template>

<script type="text/ecmascript-6">
    import Header from '@/components/Header'
    import TabBar from '@/components/TabBar'
    import Login from '@/components/Login'
    export default {
        name: "Movie",
        data() {
            return {}
        },
        methods: {},
        components : {
            Header,TabBar,Login
        }
    }
</script>

<style scoped>

</style>
