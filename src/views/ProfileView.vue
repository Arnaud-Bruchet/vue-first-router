<template>
	<div class="profil">
		<div class="card">
			<h1>Arnaud</h1>
			<h3>Formation via CCI</h3>
			<h6>Promo 2022/2023</h6>
		</div>
		<div class="card">
			<h1>------</h1>
			<h3>Formation via CCI</h3>
			<h6>Promo 2022/2023</h6>
		</div>
		<div class="card">
			<h1>------</h1>
			<h3>Formation via CCI</h3>
			<h6>Promo 2022/2023</h6>
		</div>
	</div>
</template>

<script>

export default {
  name: 'ProfileView',
	created() {},
	data:() => ({

	}),
  components: {},
}
</script>

<style scoped>
.profil {
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	grid-gap: 50px;
}

.card {
	border: 1px solid azure;
}
</style>