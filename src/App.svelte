<script>
	import LeftNav from './components/LeftNav.svelte'
	
	
</script>

<main>
	<div class="left-nav">
		<LeftNav />
	</div>
	<div class="main-content">
		fgdfgd
	</div>
	<div class="now-playing">
		sgfdsg
	</div>
</main>

<style type="text/css" lang="scss">

	main{
		display: grid;
		grid-template-columns: 0.1fr 1fr;
		grid-template-rows: 1fr 0.1fr;
		grid-template-areas: "left-nav main-content"
							 "now-playing now-playing";
		height: 100vh;
	}

	.left-nav{
		grid-area: left-nav;
	}
	.main-content{
		grid-area: main-content;
		margin-top:20px;
	}
	.now-playing{grid-area: now-playing;}
	.left-nav, .main-content, .now-playing{
		border:1px solid black;


	}

</style>

