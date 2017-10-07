<template>
  <div id="app">
    <router-view></router-view>
    <wk-head></wk-head>
  </div>
</template>

<script>
    import Head from '@/components/Public/Head'

    export default {
        name: 'app',
        data() {
            return {

            }
        },
        methods: {

        },
        components: {
            'wkHead': Head
        }
    }
</script>
<style>
    body {
        background: #161616;
        font-family: "Poppins", sans-serif;
        color: #fff;
        font-size: 16px;
        font-weight: 400;
        line-height: 24px;
    }
    
    a {
        color: #fff;
    }
</style>