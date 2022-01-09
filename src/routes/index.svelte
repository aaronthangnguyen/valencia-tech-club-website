<script>
	import Link from '../components/navigation/Link.svelte';
	import DiscordLink from '../components/navigation/DiscordLink.svelte';
</script>

<svelte:head>
	<title>Valencia Tech Club</title>
</svelte:head>
<h1 class="text-4xl font-bold">Valencia Tech Club</h1>
<p>
	Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempore aut vel nobis corporis impedit
	mollitia necessitatibus obcaecati incidunt repudiandae, provident beatae aliquid delectus libero
	dolore quis veniam excepturi itaque qui!
</p>
<div class="flex items-center gap-4">
	<DiscordLink />
	<Link href="/">Sign Up</Link>
</div>
