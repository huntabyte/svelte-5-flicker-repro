<script lang="ts">
	import * as Tooltip from '$lib/components/ui/tooltip';
	import pkgJson from '../../package.json';
</script>

<div class="flex flex-col items-start gap-8 p-40">
	<h1 class="text-lg font-semibold">Svelte Version: {pkgJson.devDependencies.svelte}</h1>
	<Tooltip.Root>
		<Tooltip.Trigger>Hover me a few times to reproduce the issue</Tooltip.Trigger>
		<Tooltip.Content>Hello world</Tooltip.Content>
	</Tooltip.Root>

	<p class="text-xs">Change Svelte to: &gtnext-140 to see the issue</p>
</div>
