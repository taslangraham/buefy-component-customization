<script lang="ts" src="./glitch-button.ts"></script>
<style scoped src="./glitch-button.scss" lang="scss"></style>
<template>
	<div class="[ text-center ] glitch-button">
		<!-- Customized Buefy button -->
		<b-button class="button1" type="is-info">
			<span>Customized!</span>
			<BIcon pack="fas" :icon="active ? 'chevron-up' : 'chevron-down'" />
		</b-button>
	</div>
</template>

