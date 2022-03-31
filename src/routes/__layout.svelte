<script>
	import Meta from "../components/meta.svelte"
	import '../app.css';

	const title = "Svelte kit template"
	const description = "Svelte kit template with tailwindcss"
	const image = null
	const url = "https://sveltekit-template.ronnapat.me/"
	const twitter = "ronnapatp"
	const keyword = "sveltekit"
</script>

<Meta title={title} description={description} image={image} url={url} twitter={`@${twitter}`} keyword={keyword} />

<main>
	<slot />
</main>