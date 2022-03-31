<script>
    export let url
    export let title
    export let image
    export let description
    export let twitter
    export let keyword
</script>
<svelte:head>
	<title>
        {title}
      </title>
      <meta property="og:url" content={url} />
      <meta property="og:type" content="website" />
      <meta property="og:title" content={title} />
      <meta property="og:description" content={description} />
      <meta property="og:image" content={image} />
      <meta property="og:keywords" content={keyword} />
      <meta name="twitter:card" content="summary_large_image" />
      <meta name="twitter:site" content={twitter} />
      <meta name="twitter:title" content={title} />
      <meta name="twitter:description" content={description} />
      <meta name="twitter:creator" content={twitter} />
      <meta name="twitter:image:src" content={image} />
      <meta name="twitter:domain" content={url} />
</svelte:head>