<template>
    <div>
        <b-nav pills fill>
            <b-nav-item :class="{active:name=='Home'}">Home{{curpage}}</b-nav-item>
            <b-nav-item :class="{active:name=='Login'}">Login</b-nav-item>
            <b-nav-item :class="{active:name=='Wiki'}">Wiki</b-nav-item>
            <b-nav-item :class="{active:name=='Play'}">Play</b-nav-item>
        </b-nav>
    </div>

</template>

<script>
    export default {
        name: "NavigationBar",
        props:["curpage"]
    }
</script>

<style scoped>

</style>