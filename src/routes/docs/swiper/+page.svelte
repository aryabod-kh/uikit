<script>
	import Swiper from '$lib/components/Swiper/Swiper.svelte';
	// import { register } from 'swiper/element/bundle';
	// // register Swiper custom elements
	// register();
</script>

<Swiper navigation pagination slidesPerView="6">
	{#each { length: 10 } as _, i}
		<swiper-slide>
			<img src="https://daisyui.com/images/stock/photo-1534528741775-53994a69daeb.jpg" alt="" />
		</swiper-slide>
	{/each}
</Swiper>
