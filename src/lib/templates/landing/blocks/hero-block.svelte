<!-- Description: Hero block component -->
<script lang="ts">
	import HeroActivityBlock from '$lib/templates/landing/blocks/hero-activity-block.svelte';
	import HeroSignup from '$lib/templates/landing/widgets/hero-signup.svelte';
	import HeroText from '$lib/templates/landing/widgets/hero-text.svelte';
	export let text_light_blue: string = '';
	export let text: string = '';
	export let subtitle: string = '';
	export let no_signup: boolean = false;
	export let activities_column_on_mobile: boolean = false;
</script>

<assembly class="flex flex-col items-start self-stretch gap-8">
	<HeroText {text_light_blue} {text} {subtitle} />
	{#if !no_signup}
		<HeroSignup />
	{/if}
	<div class="w-full flex items-center justify-center">
		<HeroActivityBlock activities_column={activities_column_on_mobile}>
			<slot />
		</HeroActivityBlock>
	</div>
</assembly>
