<script setup>
import MainHeader from './MainHeader.vue';
import MainFooter from './MainFooter.vue';
</script>

<template>
    <div class="pt-2 bg-white" >
        <MainHeader class="bg-white" />
        <slot></slot>
    </div>
    <div class="pt-20 bg-white">
        <MainFooter />
    </div>

</template>