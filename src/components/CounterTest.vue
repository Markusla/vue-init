<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const { count, increment } = useCounterStore()
</script>

<template>
	<counter>
		<button @click="increment">click to count up: {{ count }}</button>
	</counter>
</template>

<style scoped></style>
