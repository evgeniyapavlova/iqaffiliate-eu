<script>
	import AllBlocks from '$comps/AllBlocks.svelte';
	import meta_img from '$lib/images/meta__img__en.jpg';

	const title = 'IQOPTION EUROPE LTD (IQ Option EU) OFFICIAL AFFILIATE PROGRAM';
	const desc =
		"Our unique platform gives you the right tools to enhance your efforts. You can focus on your traffic, and we'll do the rest.";
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={desc} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={desc} />
	<meta property="og:image" content={meta_img} />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={desc} />
	<meta name="twitter:image" content={meta_img} />
</svelte:head>

<AllBlocks />
