<template>
	<div>
		<p>Welcome to a demo of how styles are being processed by dev servers</p>

    <h4>Dev Servers under scope are:</h4>
		<ul>
			<li>- Webpack</li>
			<li>- Vite</li>
		</ul>
	</div>
</template>

<style data-pg-id="101">
	@import './assets/base.css';
	/* @import '@/assets/base.css'; */

  p, .pg-node-id-2 {
		color: #5add64;
		padding-bottom: 10px;
	}
</style>

<style lang="scss" scoped data-pg-id="102">
	ul, .pg-node-id-3 {
		li, .pg-node-id-4 {
			margin: 10px;
		}
	}
</style>
