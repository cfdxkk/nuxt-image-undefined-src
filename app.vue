<script setup lang="ts">
	const imageUrl = ref<string>();
	if (false) {
		imageUrl.value = 'foo.jpg'
	}
</script>

<template>
	<NuxtImg :src="imageUrl" />

	<!-- or  -->
	<!-- <NuxtImg :src="undefined" /> -->
</template>