<script type="text/javascript">
	
</script>
<main>
	<form class="uk-search uk-search-default">
	    <span uk-search-icon></span>
	    <input class="uk-search-input" type="search" placeholder="Search for songs, artists & albums....">
	</form>
	<div class="user">
		<span class="bell" uk-icon="icon:bell; ratio:1.5">
			<span class="uk-badge">3</span>
		</span>
		<div class="avater">
			<div>
				<img src="../images/user.jpg" alt="user-image">
			</div>
		</div>
		<p>Buhlebethu Mkhonta</p>
	</div>
	
</main>


<style type="text/css">
	main{
		display: flex;
		align-items: center;
		justify-content: space-between;
		padding-right: 20px; 


	}
	.uk-search{
		width: 20rem;
		
	}
	.uk-search-input{
		border-radius: 20px;
		
	}
	.uk-search-input:focus{
		border-color: var(--darkgreen);

	}
	
	.user{
		display: flex;
		align-items: center;
		gap:13px;
	}
	.bell{
		position:relative; 
		transition: var(--transition);
	}
	.bell:hover{
		color:var(--darkgreen);
	}
	.uk-badge{
		position: absolute;
  		top: -10px;
  		right: -5px;
  		z-index: 1;
  		background-color: var(--darkgreen);	
	}
	.user p{
		color: white;
	}

	.avater img{
		width: 30px;
		height: 30px;
		border-radius: 50px;
	}
	
</style>