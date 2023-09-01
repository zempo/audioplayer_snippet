<script>
	import AudioPlayer from '$lib/components/audio/AudioPlayer.svelte';
</script>

<header>
	<h1>Audioplayer Snippet</h1>
</header>
<main>
	<AudioPlayer />
</main>

<style lang="scss">
	h1 {
		text-align: center;
	}
	main {
		width: 95vw;
		max-width: 1200px;
		margin: auto;
	}
</style>
