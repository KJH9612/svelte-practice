<script>
	import Header from './header.svelte'
	import Content from './content.svelte'
	import Footer from './footer.svelte'

	let count = 0;
	const handleClick = () => count = count + 1;
</script>

<Header />
<Content />
<Footer />
<button on:click={handleClick}>
	클릭수 {count}
</button>