<script>
	import LeftNav from './components/LeftNav.svelte'
	import MainContent from './components/MainContent.svelte'

	
	
</script>

<main>

	<div class="top">
		<div class="left-nav">
			<LeftNav />
		</div>
		<div class="main-content">
			<MainContent/>
		</div>
	</div>

	<div class="bottom">
		<div class="now-playing">
			now playing
		</div>
	</div>

</main>

<style type="text/css">
	main{
		display:flex;
		flex-direction: column;
	}
	.top{
		display: flex;
	}

	.left-nav{
		width: 20%;
	}
	.main-content{
		width: 100%;
		


	}

	













	/*main{
		display: grid;
		grid-template-columns: 0.2fr 1fr;
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
		
	}
	.now-playing{grid-area: now-playing;}
	.left-nav, .main-content, .now-playing{
		border:1px solid black;


	}*/

</style>

