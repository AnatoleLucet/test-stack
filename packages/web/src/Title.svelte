<script type="typescript">
	export let name: string;
</script>

<h1>Hello {name}!</h1>

<style type="scss">
	h1 {
		$color: red;

		color: $color;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
</style>
