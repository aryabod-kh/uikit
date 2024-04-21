<script>
	import Tabs from '$lib/components/Tabs/Tabs.svelte';
	import TabItem from '$lib/components/Tabs/TabItem.svelte';
	let selected = '2';
</script>

<div class="w-4/12 mx-auto">
	{selected}
	<Tabs bind:selected>
		<TabItem title="Tab 1" value="1"><div class="p-10">Tab 1</div></TabItem>
		<TabItem title="Tab 2" value="2"><div class="p-10">Tab 2</div></TabItem>
		<TabItem title="Tab 3" value="3"><div class="p-10">Tab 3</div></TabItem>
	</Tabs>
	<Tabs bind:selected variant="lift">
		<TabItem title="Tab 1" value="1"><div class="p-10">Tab 1</div></TabItem>
		<TabItem title="Tab 2" value="2"><div class="p-10">Tab 2</div></TabItem>
		<TabItem title="Tab 3" value="3"><div class="p-10">Tab 3</div></TabItem>
	</Tabs>
	<Tabs bind:selected variant="box">
		<TabItem title="Tab 1" value="1"><div class="p-10">Tab 1</div></TabItem>
		<TabItem title="Tab 2" value="2"><div class="p-10">Tab 2</div></TabItem>
		<TabItem title="Tab 3" value="3"><div class="p-10">Tab 3</div></TabItem>
	</Tabs>

	<div role="tablist" class="mt-10 daisy-tabs daisy-tabs-boxed">
		<input type="radio" name="my_tabs_1" role="tab" class="daisy-tab" aria-label="Tab 1" />
		<div role="tabpanel" class="daisy-tab-content p-10">Tab content 1</div>

		<input type="radio" name="my_tabs_1" role="tab" class="daisy-tab" aria-label="Tab 2" checked />
		<div role="tabpanel" class="daisy-tab-content p-10">Tab content 2</div>

		<input type="radio" name="my_tabs_1" role="tab" class="daisy-tab" aria-label="Tab 3" />
		<div role="tabpanel" class="daisy-tab-content p-10">Tab content 3</div>
	</div>
</div>
