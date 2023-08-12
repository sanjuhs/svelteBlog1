<script>
	export let data;
	console.log('heloowow');
	console.log(data);
	console.log(data.post);
</script>

<h1>
	{data.post.title}
</h1>
<div>{@html data.post.content}</div>
