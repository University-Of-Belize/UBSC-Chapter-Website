<!-- Section Two of landing page -->
<script lang="ts">
	import Activity from '$lib/components/public/widgets/dynamic/activity.svelte';
	import HeroBlock from '$lib/templates/landing/blocks/hero-block.svelte';
</script>

<HeroBlock
	no_signup
	text="Who are we?"
	subtitle="The Association for Computing Machinery (ACM) is the world's largest scientific and educational computing society. The University of Belize’s chapter of the ACM is only the second Student Chapter in Central America, and a part of the growing ACM network. The ACM offers members the opportunity to be an active part of the association by organizing activities such as technical talks, forums, field trips, and programming contests."
>
	<Activity data={{ title: 'Global members', number: '100,000+' }} />
	<Activity data={{ title: 'Professional chapters', number: '180+' }} />
	<Activity data={{ title: 'Student chapters', number: '680+' }} />
</HeroBlock>
