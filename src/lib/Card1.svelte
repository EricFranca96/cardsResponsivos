<script>
	import CardHeader from './CardHeader.svelte';
	import CardBody from './CardBody.svelte';
	import CardFooter from './CardFooter.svelte';
</script>

<div class="card card-1">
	<!-- Card header -->
	<CardHeader />

	<!--Card Body-->
	<CardBody />

	<!--Card Footer-->
	<CardFooter />
</div>





<style>
	.card {
		width: 300px;
		height: 460px;
		margin: 25px;
		background-color: #fff;
		border-radius: 20px;
		overflow: hidden;
		box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.7);
	}
</style>
