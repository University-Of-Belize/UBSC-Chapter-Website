<!-- Section One of landing page -->
<script lang="ts">
	import HeroBlock from '$lib/templates/landing/blocks/hero-block.svelte';
	import HeroPillBlock from '$lib/templates/landing/blocks/hero-pill-block.svelte';
</script>

<assembly class="flex justify-between items-start gap-20">
	<HeroBlock />
	<HeroPillBlock />
</assembly>
