<script type="text/javascript">
	import NavItem from '../shared/NavItems.svelte'
	import PlaylistItems from '../shared/Playlist.svelte'
	
</script>

<main>
	<div class="logo" lang="scss">
		<i class="fa-brands fa-spotify"></i>
		<p>Spotify</p>
	</div>

	<div class="navigation">
		<NavItem icon={"fa-solid fa-house-chimney"} navText={"Home"}/>
		<NavItem icon={"fa-solid fa-magnifying-glass"} navText={"Browse"}/>
		<NavItem icon={"fa-solid fa-radio"} navText={"Radio"}/>
	</div>

	
	<div class="library">
		<h3>Library</h3>
		<NavItem icon={"fa-solid fa-user"} navText={"Artists"}/>
		<NavItem icon={"fa-solid fa-compact-disc"} navText={"Albums"}/>
		<NavItem icon={"fa-regular fa-heart"} navText={"Favorite Songs"}/>
		
	</div>
	<h3>Playlist</h3>
	<div class="playlist">
		<PlaylistItems />
	</div>

</main>

<style type="text/css" lang="scss">
	main{
		background-color: var(--black);
		height:100%;
	}

	h3{
		padding-left:20px;
		color: white;
		font-size:18px;
		margin-bottom: 5px;
		font-weight: 500px;
		letter-spacing: 2px;

	}

	.logo{
		display: flex;
		align-items: center;
		padding-left: 15px;
	}
	.logo i, p{
		margin-right: 5px;
		color: var(--darkgreen);
		font-size: 25px;
	}

	.navigation, .library{
		line-height: 3rem;
		margin-top: -10px;
	} 

	.playlist{
		height:100px;
		overflow-y:auto;
		
	}



</style>