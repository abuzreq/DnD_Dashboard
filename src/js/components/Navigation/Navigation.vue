<template>
	<nav class="nav-top py-2">
		<div class="container d-flex flex-row">
			<h2 class="nav-branding pt-2">Branding</h2>

			<ul class="nav-list">
				<li class="nav-item">
					<router-link class="nav-link" :to="{ name: 'home' }">
						Home
					</router-link>
				</li>
			</ul>

			<ul class="nav-list ml-auto">
				<li class="nav-item">
					<a class="nav-link" href="#">
						Sign Up
					</a>
				</li>
				<li class="nav-button">
					<button class="btn btn-primary">Login</button>
				</li>
			</ul>
		</div>
	</nav>
</template>

<script>
	export default {
		name: 'Navigation',
	}
</script>
