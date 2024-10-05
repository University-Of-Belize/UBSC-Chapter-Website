<script lang="ts">
	import { Button } from '$lib/vendor/shadcn/components/ui/button';
	import PublicNav from '$lib/components/public/nav.svelte';
	import SectionOne from '$lib/templates/landing/sections/section-one.svelte';
</script>

<page class="inline-flex flex-col items-center gap-32 w-full h-full">
	<PublicNav />
	<main class="flex flex-col items-center gap-16 self-stretch mx-2 lg:mx-20">
		<SectionOne />
	</main>
</page>
