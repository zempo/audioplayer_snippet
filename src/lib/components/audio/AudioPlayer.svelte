<script>
	import AudioHead from './AudioHead.svelte';
	import Tracklist from './Tracklist.svelte';
	import Controls from './Controls.svelte';
	import Slider from './Slider.svelte';
</script>

<section class="player_container">
	<AudioHead />
	<div class="player_body">
		<audio />
		<Slider />
		<Controls />
		<Tracklist />
	</div>
</section>

<style lang="scss">
	.player_container {
		border: 1px solid black;
		width: 100%;
		max-width: 800px;
		margin: auto;
	}
</style>
