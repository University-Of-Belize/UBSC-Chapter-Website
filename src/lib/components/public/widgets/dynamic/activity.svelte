<script lang="ts">
	type Data = {
		number: string;
		title: string;
		link?: string;
		linkText?: string;
	};
	export let data: Data = {
		number: '#####Z',
		title: 'Activity Data',
		link: '/activity-link',
		linkText: 'Learn More'
	};

	export let size: string = '';
	export let center: boolean = false;
</script>

<preload class="hidden text-5xl text-center md:text-left" />
<component
	class="flex flex-col text-center {center ? 'md:text-center' : 'md:text-left'} justify-center items-center w-full md:w-fit gap-0.5"
>
	<div class="font-extralight {size ? size : 'text-5xl'} text-sky-500 w-full">
		{data.number}
	</div>
	<div class="text-xl font-medium text-slate-800 w-full">
		{data.title}
	</div>
</component>
