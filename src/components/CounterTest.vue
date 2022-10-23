<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>

<template>
	<counterbtn>
		<button @click="counter.increment">
			click me to count up {{ counter.count }}
		</button>
	</counterbtn>
</template>

<style scoped></style>
