<script>
	import Header from "$lib/header.svelte";

</script>

<Header/>
<section
	id="landing"
	class="flex flex-col justify-center 
		bg-gradient-to-r 
		min-h-[95vh]
		custom-gradient"
>
	<div class="pl-10">
		<h1 class="pt-10 text-7xl text-white">Hey, I am <br /> Adwithya Magow</h1>
		<h2 class="font-serif pt-12 text-3xl text-white">I'm a full-stack developer</h2>
	</div>
</section>

<style>
	.custom-gradient {
		background-image: linear-gradient(
			to right top,
			#d16ba5,
			#c777b9,
			#ba83ca,
			#aa8fd8,
			#9a9ae1,
			#8aa7ec,
			#79b3f4,
			#69bff8,
			#52cffe,
			#41dfff,
			#46eefa,
			#5ffbf1
		);
	}
</style>
