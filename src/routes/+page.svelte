<script lang="ts">
	import { Button } from '$lib/vendor/shadcn/components/ui/button';
	import PublicNav from '$lib/components/public/nav.svelte';
	import SectionOne from '$lib/templates/landing/sections/section-one.svelte';
</script>

<page class="inline-flex flex-col items-center gap-32 w-full h-full">
	<PublicNav />
	<main class="flex flex-col items-center gap-16 self-stretch">
		<SectionOne />
		<h1 class="text-4xl">ShadCN Test</h1>
		<Button>Click me</Button>
	</main>
</page>
