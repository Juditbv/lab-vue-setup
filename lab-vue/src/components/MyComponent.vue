<template>
	<div>hello {{ name }}</div>
	<button @click="helloWorld()">Button log</button>
</template>

<script setup>
	import { ref } from "vue";

	const name = ref("Judit");
	const helloWorld = () => console.log("Hello World!");
</script>

<style scoped>
</style>