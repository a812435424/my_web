<template>
  <div class="head">
    <div class="header">
      <div class="logo">
        <a href="/">00 | Web developer</a>
      </div>
      <div class="nav">
        <a href="">About</a>
        <a href="">Projects</a>
        <a href="">Contact</a>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: 'head',
        data() {
            return {
                msg: '125151'
            }
        }
    }
</script>

<style>
    .head {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 65px;
        line-height: 65px;
        overflow: hidden;
    }
    
    .logo {
        margin-left: 80px;
        float: left;
    }
    
    .nav {
        float: right;
        margin-right: 20px;
        overflow: hidden;
    }
    
    .nav a {
        margin-right: 60px;
        position: relative;
    }
    
    .nav a:after {
        content: "";
        position: absolute;
        top: 23px;
        left: 0;
        width: 0;
        height: 1px;
        background: #fff;
        opacity: 0;
        transition: all 0.5s;
        -moz-transition: all 0.5s;
        /* Firefox 4 */
        -webkit-transition: all 0.5s;
        /* Safari 和 Chrome */
        -o-transition: all 0.5s;
        /* Opera */
    }
    
    .nav a:hover:after {
        width: 100%;
        opacity: 0.9;
    }
</style>
