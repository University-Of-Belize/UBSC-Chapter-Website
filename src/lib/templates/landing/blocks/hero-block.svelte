<!-- Description: Hero block component -->
<script lang="ts">
	import Activity from '$lib/components/public/widgets/dynamic/activity.svelte';
	import HeroSignup from '$lib/templates/landing/widgets/hero-signup.svelte';
</script>

<component class="flex flex-col items-start self-stretch gap-8">
	<article class="flex flex-col items-start gap-3">
		<div class="font-light text-5xl text-sky-500">
			Belize's <span class="text-sky-600">First ACM Chapter</span>
		</div>
		<p class="self-stretch inter text-sm font-normal leading-snug">
			The University of Belize's Associate for Computer Machinery (ACM) Chapter (UBACM) at The
			University of Belize is dedicated to upskilling and informing Belizeans about Technology.
		</p>
	</article>
	<HeroSignup />
	<activity-group class="flex justify-between items-start self-stretch w-full">
		<Activity data={{ title: 'Active student groups', number: '400' }} />
		<Activity data={{ title: 'Completed projects', number: '0' }} />
	</activity-group>
</component>
