<script lang="ts">
	export let name = '';
	export let props: any = [];

	function propAttr(prop: any) {
		const string = prop.split(':');
		console.log(string, 'biya ino bebin');
		return string;
	}
</script>

<span>
	&lt;<span class="text-green-600">{name}</span>
	{#each props as prop, index}
		{@const propValues = propAttr(prop)}
		<span>
			{propValues[0]}{#if propValues[1]}="{propValues[1]}"{/if}
		</span>
		{#if index < props.length - 1}
			<span></span>
		{/if}
	{/each}
	<span>&gt;</span>
	<slot />
	&lt;/<span class="text-green-600">{name}</span>&gt;
</span>
