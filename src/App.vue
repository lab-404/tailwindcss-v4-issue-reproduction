<script setup lang="ts">
</script>

<template>
  <button class="btn">alsdkjflaksdjf</button>
</template>

<style scoped lang="css">
.btn {
    @apply cursor-pointer aspect-video h-full w-full inline-flex items-center justify-center shadow rounded-md border border-gray-200 bg-white text-gray-700 font-semibold focus:outline-hidden hover:text-white hover:disabled:bg-white hover:disabled:text-gray-400 disabled:text-gray-400 disabled:cursor-not-allowed transition-all ease-in-out duration-300;
}

.number {
    @apply hover:bg-blue-600;
}

.number.active {
    @apply bg-blue-600 text-white;
}

.backspace {
    @apply hover:bg-red-600;
}

.backspace.active {
    @apply bg-red-600 text-white;
}

.submit {
    @apply hover:bg-green-600;
}

.submit.active {
    @apply bg-green-600 text-white;
}
</style>
