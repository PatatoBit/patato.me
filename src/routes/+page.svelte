<div class="wrapper">
	<br />

	<div class="hero">
		<div class="hero-text">
			<div>
				<p class="label">hi there, welcome to</p>
				<h1>Pat's corner of the internet</h1>
			</div>
			<p>stick around if you'd like, there are some fun stuffs here</p>
		</div>

		<img src="/pfp.jpeg" alt="Patato" />
	</div>
	<hr />
</div>

<style lang="scss">
	.hero {
		display: flex;
		justify-content: space-between;
		align-items: center;
		flex-wrap: wrap-reverse;
		gap: 2rem;

		.hero-text {
			display: flex;
			flex-direction: column;
			gap: 0.1rem;
		}

		img {
			width: 7rem;
			aspect-ratio: 1;
			border-radius: 50%;
		}

		h1 {
			line-height: 0.5;
		}
	}
</style>
