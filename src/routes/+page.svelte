<script>
	import Checkbox from '$lib/components/Checkbox/Checkbox.svelte';
	import Divider from '$lib/components/Divider/Divider.svelte';
</script>

<div class="p-4">
	<Divider></Divider>
	<div class="flex">
		<div class="w-40 h-40 daisy-card bg-primary"></div>
		<Divider color="primary" horizontal>OR</Divider>
		<div class="w-40 h-40 daisy-card bg-secondary"></div>
		<Divider color="secondary" horizontal>OR</Divider>
		<div class="w-40 h-40 daisy-card bg-accent"></div>
	</div>
	<Divider>OR</Divider>
	<Divider start>Start</Divider>
	<Divider end>end</Divider>

	<Divider color="primary">OR</Divider>
	<Divider color="secondary">OR</Divider>
	<Divider color="accent">OR</Divider>
	<Divider color="success">OR</Divider>
	<Divider color="info">OR</Divider>
	<Divider color="error">OR</Divider>
	<Divider color="warning">OR</Divider>
	<Divider color="natural">OR</Divider>

	<Divider size="lg"></Divider>
</div>
