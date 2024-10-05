<!-- Pill component -->
<script lang="ts">
	export let background: string = '';
	export let text: string = '<No text provided>';
</script>

<component
	class="flex flex-col items-start gap-4 bg-cover rounded-lg w-full h-64 px-6 py-8"
	style="background-image: {background
		? `url(${background})`
		: ''}; background-repeat: no-repeat; background-color: lightgray;"
>
	<article class="text-3xl text-slate-50 font-extralight self-stretch flex-1">{text}</article>
</component>
