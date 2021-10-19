<template>
	<div id="app">
		<Scene />
	</div>
</template>

<script>
import Scene from './components/Scene.vue';

export default {
	name: 'App',
	components: {
		Scene,
	},
};
</script>

<style>
html,
body,
#app {
	margin: 0px;
	overflow: hidden;
}
</style>
