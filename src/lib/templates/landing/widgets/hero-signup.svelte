<script lang="ts">
	import { Input } from '$lib/vendor/shadcn/components/ui/input';
	import { Label } from '$lib/vendor/shadcn/components/ui/label';
	import Button from '$lib/vendor/shadcn/components/ui/button/button.svelte';
</script>

<component class="w-full">
	<input-combo class="grid w-full items-center gap-1.5">
		<Label for="email-2">Email</Label>
		<div class="flex items-start gap-1.5 self-stretch">
			<Input type="email" id="email-2" placeholder="Enter your email address" />
			<Button class="bg-sky-500 hover:bg-sky-600">Subscribe</Button>
		</div>
		<p class="text-muted-foreground text-sm">Enter your email address.</p>
	</input-combo>
</component>
