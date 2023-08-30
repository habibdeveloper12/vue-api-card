<template>
  <a
    :href="href"
    target="_blank"
    class="px-3 py-2 rounded border-2 text-white border-blue-600 bg-blue-500 hover:bg-red-600 transition-colors"
  >
    <slot>Go Link</slot>
  </a>
</template>

<script setup>
const props = defineProps({
  href: String,
});
</script>
