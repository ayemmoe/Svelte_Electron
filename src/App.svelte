<script>
	import FileDir from './FileDir.svelte';
	
</script>

<main>
<h1>File Tree</h1>

<FileDir />

</main>

<style>
    main {
		text-align: left;
		float: left;
		width: 100%;		 
		max-width: 240px;
		margin: 0 auto;
		padding: 0.1em;
		background-color: rgb(241, 221, 221);
		color: rgb(66, 60, 60)

    }

	h1 {
		color: black;
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 100;
	}

	fileArea {
		width: 100%;
		height: auto;
		background-color: burlywood;
		color: black;
	}
	
</style>


