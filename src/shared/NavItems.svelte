<script type="text/javascript">
	export let icon 
	export let navText
	
	
	
	

</script>

<main >
	<span>
	<a href={"#"}> <i class={icon}></i> {navText} </a></span>
</main>
<style type="text/css">
	main{
		display:flex;
		align-items:center;
		
		padding-left: 20px; 
		transition: var(--transition);

	}
	span{
		font-size: 15px;
		color:var(--textColor);
		transition: var(--transition);
	}

	i{margin-right: 5px;}
	a{
	 	text-decoration: none;	
	 	color: var(--textColor);
	 	transition: var(--transition);
	 }

	 main:hover{
	 	border-left:1px solid var(--darkgreen);
	 	border-left-width: 5px;
	 	transition: var(--transition);
	 }
	 a:hover{
	 	color: white;
	 	text-decoration:none;
	 }
	 
	 



	 
	 

</style>