<script lang="ts">
	import { ScrollArea } from '$lib/components/ui/scroll-area';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<div class="my-8" />
<section class="mx-auto flex w-full max-w-3xl items-center justify-center px-0 sm:px-6">
	<div class="w-full bg-card">
		<ScrollArea type="auto" orientation="horizontal" class="flex h-24">
			<div class="flex size-full items-center justify-center">
				<div class="h-7 w-[200px] bg-red-900" />
				<div class="h-7 w-[200px] bg-red-100" />
				<div class="h-7 w-[200px] bg-red-300" />
				<div class="h-7 w-[200px] bg-red-500" />
				<div class="h-7 w-[200px] bg-red-700" />
				<div class="h-7 w-[200px] bg-red-900" />
			</div>
		</ScrollArea>
	</div>
</section>
