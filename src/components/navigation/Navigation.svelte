<script>
	import DiscordLink from './DiscordLink.svelte';
	import Link from './Link.svelte';
</script>

<nav class="flex items-center justify-end gap-4 mt-4 mb-8">
	<Link href="/">Home</Link>
	<Link href="/projects">Project</Link>
	<Link href="/events">Events</Link>
	<Link href="/people">People</Link>
	<DiscordLink />
</nav>
