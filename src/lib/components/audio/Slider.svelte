<script></script>

<div class="slider">
	<div class="time_disp">
		<span>Current Time</span>
		<span>Duration</span>
	</div>
	<label for="track_progress" class="timestamps">
		<!-- TODO: Timestamps -->
		<input type="range" name="track_progress" id="track_progress" />
	</label>
</div>

<style lang="scss">
	.slider {
		padding: 1.5rem 1.5rem 0.75rem;
		margin: auto;
		max-width: 40rem;
		margin-bottom: 1rem;
		.time_disp {
			width: 100%;
			margin: auto;
			display: flex;
			justify-content: space-between;
			span {
				line-height: 1.75;
				font-weight: bold;
			}
		}
		.timestamps {
			width: 100%;
			position: relative;
			input[type='range'] {
				width: 100%;
				margin: auto;
			}
		}
	}
</style>
