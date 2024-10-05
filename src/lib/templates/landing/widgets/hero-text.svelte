<script lang="ts">
	export let text: string = '<no text provided>';
	export let text_light_blue: string = '';
	export let subtitle: string = '<no subtitle provided>';
</script>

<article class="flex flex-col items-start gap-3">
	<div class="font-light text-5xl text-sky-500">
		{text_light_blue} <span class="text-sky-600">{text}</span>
	</div>
	<p class="self-stretch inter text-sm font-normal leading-snug">
		{subtitle}
	</p>
</article>
