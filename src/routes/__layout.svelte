<script lang="ts">
	import '../app.scss';
</script>


<main>
	<slot />
</main>


<style lang="scss">
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	@media (min-width: 480px) {
	
	}
</style>
