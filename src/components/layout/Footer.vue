<script setup>
import { computed } from 'vue';

const currentYear = computed(() => new Date().getFullYear());
</script>

<template>
<footer class="w-full text-center p-8 border-t border-gray-200 dark:border-white/10 mt-8">
<p class="text-xs text-gray-500 dark:text-gray-400">
Copyright © {{ currentYear }}
<a
href="https://qm.qq.com/q/eFGTsckPjq"
target="_blank"
rel="noopener noreferrer"
class="font-semibold text-indigo-600 dark:text-indigo-400 hover:underline"
>
苹果签VPN加速
</a>.
All Rights Reserved.
</p>
</footer>
</template>
