<script type="text/javascript">
	
</script>

<main>
	<div class="view-tranding">
		<h1>Trending</h1>
		<a href={"#"}>More<span uk-icon="icon: chevron-right; ratio: 1"></span></a>
	</div>
	<div class="uk-child-width-1-2@m" uk-grid>

	</div>
	<div class="trending-song uk-cover-container uk-height-medium">
		<div class="cover">
   			 <img src="../images/group-black-min.jpg" alt="group" uk-cover>
		</div>
		<div class="info">
			<p>Artist<span></p>
			<h1>Dreamcatcher</h1>
			<div class="buttons">
				<button class="play">PLAY</button>
				<button class="follow">FOLLOW</button>
			</div>
		</div>   
</main>

<style type="text/css">
	p,h1{
		color: white;
	
	}
	h1{
		font-size: 25px;
	}
	a{
		color: white;
		text-decoration: none;
	}
	a:hover{
		color: var(--lightgreen);
	}
	
	.view-tranding{
		display: flex;
		align-items: center;
		justify-content: space-between;
	}
	.trending-song{
		position: relative;
		width: 100%;
		height: 15rem;
		border-radius: 15px;
		box-shadow: 20px 20px 50px rgba(0,0,0,0.25);
		backdrop-filter:blur(8px);
		-webbackdrop-filter:blur(8px);

	}
	.info{
		position: absolute;
		bottom: 2rem;
		padding-left:20px;
		line-height: 0;
	}
	.info p{
		margin-bottom: -25px;
	}
	.info p span{margin-left:10px;}

	button{
		width: 8rem;
		height: 2rem;
		border-radius: 10px;
		cursor: pointer;
		border: none;
		margin-right: 5px;
		transition: var(--transition);
	}

	.play{
		background-color: var(--darkgreen);
		color: white;
	}
	.play:hover{
		background-color: var(--lightgreen);
		border: 1px solid white;
	}

	.follow{
		background:transparent;
		border:1px solid white;
		color: white;
	}
	.follow:hover{
		border-color: var(--lightgreen);


	}




	
</style>