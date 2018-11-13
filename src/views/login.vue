<template>
    <div>
        <p class="test" @click="toIndex()">你好</p>
        <img src="../assets/logo.png" height="200" width="200" alt="">
    </div>
</template>
<script>
import Vue from 'vue'
    export default {
        name:'login',
        data(){
            return {
                msg:"hello vue !!"
            }
        },
        methods:{
            toIndex(){
                 this.$router.push({
                    path: '/index'
                })
            }
        }
    }
</script>
<style >
    .test{
        color:#020202;
        font-size:18px;
    }
</style>
