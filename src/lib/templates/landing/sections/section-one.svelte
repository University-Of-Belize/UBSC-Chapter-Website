<!-- Section One of landing page -->
<script lang="ts">
	import HeroBlock from '$lib/templates/landing/blocks/hero-block.svelte';
	import HeroPillBlock from '$lib/templates/landing/blocks/hero-pill-block.svelte';
	import Pill from '$lib/components/public/widgets/static/pill.svelte';
	import Activity from '$lib/components/public/widgets/dynamic/activity.svelte';
</script>

<assembly class="flex justify-between items-start gap-20">
	<HeroBlock>
		<Activity data={{ title: 'Active student groups', number: '400' }} />
		<Activity data={{ title: 'Completed projects', number: '0' }} />
	</HeroBlock>
	<HeroPillBlock>
		<Pill text="Join a Global Organization" background="/landing/pill/world-map.png" />
		<Pill text="Find Your Passion" background="/landing/pill/man-holding-laptop.jpg" />
	</HeroPillBlock>
</assembly>
