<template>
    <el-button type="primary" @click="">按钮</el-button>
</template>

<script setup>
import { ref, reactive, getCurrentInstance, nextTick } from "vue"
const { proxy } = getCurrentInstance();
</script>

<style lang="scss" scoped>
</style>
