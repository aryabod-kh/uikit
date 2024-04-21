<script>
	import Button from '$lib/components/Button/Button.svelte';
</script>

<Button color="primary">Test</Button>
<div class="daisy-collapse bg-base-200">
	<input type="radio" name="my-accordion-1" checked="checked" />
	<div class="collapse-title text-xl font-medium">Click to open this one and close others</div>
	<div class="collapse-content">
		<p>hello</p>
	</div>
</div>
<div class="daisy-collapse bg-base-200">
	<input type="radio" name="my-accordion-1" />
	<div class="daisy-collapse-title text-xl font-medium">
		Click to open this one and close others
	</div>
	<div class="daisy-collapse-content">
		<p>hello</p>
	</div>
</div>
<div class="daisy-collapse bg-base-200">
	<input type="radio" name="my-accordion-1" />
	<div class="daisy-collapse-title text-xl font-medium">
		Click to open this one and close others
	</div>
	<div class="daisy-collapse-content">
		<p>hello</p>
	</div>
</div>
