<template>
  <div
    class="min-h-screen bg-gray-50 w-full transition text-gray-900 duration-100 dark:(bg-gray-900 text-gray-50) p-4"
  >
    <Header />

    <div class="container mx-auto p-10">
      <slot />
    </div>
  </div>
</template>
<setup lang="ts">
export default defineComponent({
  component: {
    name: "BaseLayout",
  },
});
</setup>
