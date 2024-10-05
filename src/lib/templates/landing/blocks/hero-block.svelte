<!-- Description: Hero block component -->
<script lang="ts">
	import HeroActivityBlock from '$lib/templates/landing/blocks/hero-activity-block.svelte';
	import HeroSignup from '$lib/templates/landing/widgets/hero-signup.svelte';
	import HeroText from '$lib/templates/landing/widgets/hero-text.svelte';
	export let text_light_blue: string = '';
	export let text: string = '';
	export let subtitle: string = '';
	export let no_signup: boolean = false;
</script>

<assembly class="flex flex-col items-start self-stretch gap-8">
	<HeroText {text_light_blue} {text} {subtitle} />
	{#if !no_signup}
		<HeroSignup />
	{/if}
	<HeroActivityBlock>
		<slot />
	</HeroActivityBlock>
</assembly>
