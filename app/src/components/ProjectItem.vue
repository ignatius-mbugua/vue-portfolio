<template>
  <div
    class="flex flex-col bg-white border border-gray-200 shadow-sm rounded-xl p-4 md:p-5 mb-8"
  >
    <h1 class="text-xl font-bold pb-4 text-gray-800">
        <slot name="heading"></slot>
    </h1>
    <p class="text-gray-500">
      <slot name="content"></slot>
    </p>
  </div>
</template>

<script setup></script>
