<template>
	<!-- <SomeDirections/> -->
	<div class="image-flex">
		<div class="image-box">
			<p>NuxtImage but src is undefined</p>
			<pre><code>&lt;NuxtImg provider="cloudflare" width="300" :src="undefined" /&gt;</code></pre>
			<NuxtImg provider="cloudflare" width="300" :src="undefined" />
		</div>
	</div>
</template>

<style>
html, body {
	padding: 0;
	margin: 0;
}
</style>

<style scoped>
	p, pre {
		margin-left: 10px;
	}

	code {
		font-size: 12px;
	}

	.image-flex {
		width: 100vw;
		height: 100vh;

		display: flex;
		flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    align-content: center;
	}

	.image-box {
		float: left;
		width: 550px;
		height: 250px;
		border: solid 1px black;
		margin-bottom: 10px;
		margin-right: 10px;
	}
</style>
