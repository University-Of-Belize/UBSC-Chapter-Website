<script lang="ts">
	export let activities_column: boolean = false;
</script>

<preload class="hidden flex-col" />
<activity-group
	class="flex sm:flex-row {activities_column ? 'flex-col' : ''} justify-between items-start self-stretch w-full"
>
	<slot />
</activity-group>
