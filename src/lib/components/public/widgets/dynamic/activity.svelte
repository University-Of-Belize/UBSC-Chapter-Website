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
</script>

<preload class="hidden text-5xl" />
<component class="flex flex-col text-center justify-center items-center w-fit gap-0.5">
	<div class="font-extralight {size ? size : 'text-5xl'} text-sky-500 w-full">
		{data.number}
	</div>
	<div class="text-xl font-medium text-slate-800 w-full">
		{data.title}
	</div>
</component>
