<template>
    <div>
        <h1>Exsample1View</h1>
        <div>
            <SampleSlot>
                <template v-slot:default>
                     <p>親コンポーネントから渡されたもの</p>
                </template>
                <!-- 名前は v-slotでも #付きでもいける -->
                <template #header>
                    <p>{{ msg }}</p>
                </template>
           </SampleSlot> 
        </div>
    </div>    
</template>

<script setup lang="ts">
    import  { ref } from 'vue'
    import SampleSlot from '@/components/SampleSlot.vue'

    const msg = ref('I\'m Exsample1View');

</script>

<style scoped>
</style>
