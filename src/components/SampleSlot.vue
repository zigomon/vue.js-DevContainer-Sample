<template>
    <div>
        <slot><span>指定がない場合に表示される</span></slot>
        <slot name="header"><span>既定のヘッダー</span></slot>
        <slot name="footer"><span>既定のフッター</span></slot>
    </div>
</template>

<script setup lang="ts">
</script>

<style scoped>
</style>
