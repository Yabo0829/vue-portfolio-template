<script setup>
import MainLayout from '../components/MainLayout.vue';

// Page Title of Views
const pageTitle = 'About'
</script>

<template>
  <MainLayout :pageTitle="pageTitle">
    <section class="container mx-auto mt-8 p-4">
      <h1 class="text-3xl font-bold mb-4">About Us</h1>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

        <div class="text-gray-700">
          <p class="mb-4"><strong></strong>Name: Jessabel M. Yabo </p>
          <p class="mb-4"><strong></strong>Birthday: August 29, 2000 </p>
          <p class="mb-4"><strong></strong>Birthplace: Bangbang Cordova Cebu </p>

        </div>
      </div>
    </section>
  </MainLayout>
</template>