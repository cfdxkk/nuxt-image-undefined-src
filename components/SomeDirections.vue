<template>
	<div>
		<p>NuxtImage don't work when src is undefined.</p>
		<pre>
			<code>
export default defineNuxtConfig({
	devtools: { enabled: false },
	modules: [
		'@nuxt/image',
	],
	image: {
		provider: 'ipx',
		domains: ['i2.100024.xyz'],
		dir: 'public/'
	}
})
			</code>
		</pre>
	</div>

</template>