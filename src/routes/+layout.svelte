<script lang="ts">
	import { ScrollArea } from '$lib/components/ui/scroll-area';
	import '../app.pcss';
</script>

<ScrollArea orientation="vertical" class="h-[calc(100dvh_-_56px_-_1px)] w-full">
	<section class="app-container">
		<slot />
	</section>
</ScrollArea>
