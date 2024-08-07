<script setup>
import Button from "./Button.vue";
</script>
<template>
  <!-- Hero -->
  <div class="relative overflow-hidden">
    <!-- Background Gradient -->
    <div
      aria-hidden="true"
      class="flex absolute -top-32 start-1/2 transform -translate-x-1/2"
    >
      <div
        class="bg-gradient-to-r from-violet-300/50 to-purple-100 blur-3xl w-56 h-56 md:w-96 md:h-96"
      ></div>
    </div>
    <!-- End Background Gradient -->

    <div class="relative z-10">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 lg:py-16">
        <div class="max-w-2xl text-center mx-auto">
          

          <!-- Title -->
          <div class="mt-5 max-w-2xl">
            <h1
              class="block font-semibold text-gray-800 text-4xl md:text-5xl lg:text-6xl"
            >
              Ignatius Mbugua
            </h1>
          </div>
          <!-- End Title -->

          <div class="mt-5 max-w-3xl">
            <p class="text-lg text-gray-600">
              Web Developer
            </p>
          </div>

          <!-- Button -->
          <div class="mt-8 gap-3 flex justify-center">
            <Button>
              View Profile
              </Button>
          </div>
          <!-- End Buttons -->
        </div>
      </div>
    </div>
  </div>
  <!-- End Hero -->
</template>
