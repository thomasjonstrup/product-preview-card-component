<script lang="ts">
	let count: number = 0;
	const increment = () => {
		count += 1;
	};
</script>

<div>
	<button on:click={increment}>
		Clicks: {count}
	</button>

	<div class="attribution">
		Challenge by <a
			href="https://www.frontendmentor.io?ref=challenge"
			target="_blank">Frontend Mentor</a
		>. Coded by <a href="#">Your Name Here</a>.
	</div>
</div>

<style>
	.attribution {
		font-size: 11px;
		text-align: center;
	}
	.attribution a {
		color: hsl(228, 45%, 44%);
	}

	button {
		font-family: inherit;
		font-size: inherit;
		padding: 1em 2em;
		color: #ff3e00;
		background-color: rgba(255, 62, 0, 0.1);
		border-radius: 2em;
		border: 2px solid rgba(255, 62, 0, 0);
		outline: none;
		width: 200px;
		font-variant-numeric: tabular-nums;
		cursor: pointer;
	}

	button:focus {
		border: 2px solid #ff3e00;
	}

	button:active {
		background-color: rgba(255, 62, 0, 0.2);
	}
</style>
