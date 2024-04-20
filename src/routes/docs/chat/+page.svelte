<script>
	import Avatar from '$lib/components/Avatar/Avatar.svelte';
	import Chat from '$lib/components/Chat/Chat.svelte';
</script>

<div class="p-4">
	<Chat start color="primary">
		<div slot="image">
			<Avatar class="w-10" shape="circle">
				<img
					alt="Tailwind CSS chat bubble component"
					src="https://daisyui.com/images/stock/photo-1534528741775-53994a69daeb.jpg"
				/>
			</Avatar>
		</div>
		<div slot="header">
			Obi-Wan Kenobi
			<time class="text-xs opacity-50">12:45</time>
		</div>
		hello sir!
		<span slot="footer">Seen</span>
	</Chat>
	<Chat end color="accent">
		<div slot="image">
			<Avatar class="w-10" shape="circle">
				<img
					alt="Tailwind CSS chat bubble component"
					src="https://daisyui.com/images/stock/photo-1534528741775-53994a69daeb.jpg"
				/>
			</Avatar>
		</div>
		<div slot="header">
			Obi-Wan Kenobi
			<time class="text-xs opacity-50">12:45</time>
		</div>
		hello again<span slot="footer">Delivered</span>
	</Chat>
</div>
