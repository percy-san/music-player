<script>
	import LeftNav from './components/LeftNav.svelte'
	import MainContent from './components/MainContent.svelte'

	
	
</script>

<main>
	<LeftNav />
	<MainContent/>
</main>

<style type="text/css">
	main{
		display: grid;
		grid-template-columns: 0.2fr 1fr;
		grid-template-rows: 1fr;
		height: 100vh;
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

