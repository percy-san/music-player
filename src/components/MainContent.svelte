<script type="text/javascript">
	import Top from './top.svelte'
	import Home from './Home.svelte'
	
</script>
<div>
	<Top/>
	<div class="main-divison">
		<Home/>
		sdfsdf
	</div>
	
</div>
<style type="text/css">
	div{
		background-color: var(--black);
	}
	.main-divison{
		display: grid;
		grid-template-columns: 1fr 0.5fr;
	}
	
</style>