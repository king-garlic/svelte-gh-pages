<script>
	export let name;
</script>

<main>
	<h1>1. 소스 작업</h1>
	<h1>2. 푸시</h1>
	<h1>3. gh-pages 브랜치 에 소스 카피 : git subtree push --prefix public/ origin gh-pages</h1>
	<h1>4. 소스 확인 https://github.com/king-garlic/svelte-gh-pages/tree/gh-pages/build</h1>
	<h1>5. 페이지 확인 https://king-garlic.github.io/svelte-gh-pages/</h1>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>