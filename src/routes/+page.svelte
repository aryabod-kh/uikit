<script>
	import DatePicker from '@plantir/uikit/components/DatePicker/DatePicker.svelte';
	import TextField from '@plantir/uikit/components/TextField/TextField.svelte';
	let value = '2024-02-28';
	let formattedValue = '';
</script>

<!-- <DatePicker bind:value bind:formattedValue /> -->
<div class="border-b">
	<div class="h-16 container mx-auto flex items-center justify-between gap-3">
		<div class="flex items-center gap-2">
			<img src="/logo.jpg" class="w-8 h-8 rounded-full" alt="" />
			UiKit
		</div>
		<div>
			<TextField placeholder="search" size="sm" />
		</div>
		<div>khodafez</div>
	</div>
</div>
