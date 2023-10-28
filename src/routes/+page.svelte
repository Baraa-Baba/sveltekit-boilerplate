<script>
	let title='bdjnejklnl'
	let updatetitle=()=>{title='diffrent'}
</script>

<div>
	<h2>{title}</h2>
	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore numquam reiciendis fugit nihil quidem fuga eos necessitatibus ut, totam enim nam a adipisci, soluta incidunt mollitia facilis doloremque, blanditiis non consequatur. Deserunt sit nemo exercitationem cupiditate iure quam dolores! Ad?</p>
	<button on:click={updatetitle}>clicke me</button>
	<input type="text" bind:value={title}>
</div>
<style>
	div{
		width: 100%;
		text-align: center;
	}
</style>