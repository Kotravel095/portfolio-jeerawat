<script setup>
import MainLayout from '@/layout/MainLayout.vue';
import HeroComponent from '@/components/HeroComponent.vue';
import MySkills from '@/components/MySkills.vue';
import MyExperience from '@/components/MyExperience.vue';
import AbouthMe from '@/components/AbouthMe.vue';
</script>

<template>
  <MainLayout>
    <HeroComponent />
    <MySkills />
    <MyExperience class="mt-20" />
    <AbouthMe />
  </MainLayout>
</template>
