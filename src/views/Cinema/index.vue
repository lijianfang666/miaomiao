<template>
    <div id="main">
        <Header title="喵喵影院"></Header>
        <Clist></Clist>
        <TabBar></TabBar>
    </div>
</template>

<script type="text/ecmascript-6">
    import Header from '@/components/Header'
    import TabBar from '@/components/TabBar'
    import Clist from  '@/components/Clist'
    export default {
        name: "Movie",
        data() {
            return {}
        },
        methods: {},
        components : {
            Header,TabBar,Clist
        }
    }
</script>

<style scoped>

</style>
