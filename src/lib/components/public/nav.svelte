<script lang="ts">
	import { Button } from '$lib/vendor/shadcn/components/ui/button';
</script>

<main class="flex text-slate-50 bg-sky-950 justify-between items-center px-20 py-2">
	<div class="nav-logo flex items-center gap-1">
		<img src="/landing/stock/acm_chapter_light.png" alt="ACM Chapter Logo" width="40px" />
		<div class="font-thin text-lg">UBACM</div>
	</div>
	<div class="nav-links text-sm w-fit uppercase flex items-center gap-4 text-md font-light">
		<div>ABOUT US</div>
		<div>GROUPS</div>
		<div>COMMITEES</div>
		<div>PROJECTS</div>
		<div>CONTACT</div>
	</div>
	<Button class="bg-sky-500 hover:bg-sky-600">Login with Email</Button>
</main>
