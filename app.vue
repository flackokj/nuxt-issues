<template>
	<div>
		<HomeIcon :style="{ width: '20px', height: '20px' }" />
		<h1>{{ myUsername }}</h1>
	</div>
</template>

<script setup>
import { HomeIcon } from '@heroicons/vue/24/outline';
const myUsername = ref('username');
</script>
