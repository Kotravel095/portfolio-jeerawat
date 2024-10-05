<script setup>
import MainHeader from './MainHeader.vue';
import MainFooter from './MainFooter.vue';
</script>

<template>
    <div>
        <MainHeader class="md:pl-14 md:pr-14 pt-5" />
        <slot></slot>
        <MainFooter />
    </div>

</template>