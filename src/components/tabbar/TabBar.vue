<template>
    <div id="tab-bar">
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: "Tabbar",
    }
</script>

<style scoped>
    #tab-bar {
        /*流性布局*/
        display: flex;
        background-color: #f6f6f6;
        position: fixed;
        left: 0;
        right: 0;
        bottom: 0;
        box-shadow: 0px -1px 1px rgba(100, 100, 100, 0.1);
    }
</style>