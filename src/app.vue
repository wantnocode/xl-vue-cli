<template>
    <div id="app">
        <p class="test">111112222111111111111111111111test text</p>
        <p>{{msg}}</p>
    </div>
</template>
<script>
import Vue from 'vue'
    export default {
        name:'app',
        data(){
            return {
                msg:"hello vue !!"
            }
        },
    }
</script>
<style >
    .test{
        color:#020202;
        font-size:18px;
    }
</style>
