<script>
	import { page } from '$app/stores';
</script>

{#if $page.params.day == '1'}
	<p>
		On the first day of Christmas<br />My good friends brought to me<br />A song and a Christmas
		tree 🎄
	</p>

	<iframe
		id="rick-roll"
		width="560"
		height="315"
		src="https://www.youtube.com/embed/dQw4w9WgXcQ?controls=0&autoplay=1&loop=1"
		title="YouTube video player"
		frameborder="0"
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
		allowfullscreen
	/>

	<p>That was a silly song.<br />Might want to go to the next day.</p>
{:else if $page.params.day == '2'}
	<p>
		On the second day of Christmas<br />My good friends brought to me a wrapped gift<br />And a song
		for the Christmas tree
	</p>
{/if}
