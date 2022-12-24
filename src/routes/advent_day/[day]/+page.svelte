<script>
	import { page } from '$app/stores';
</script>

{#if $page.params.day == '1'}
	<p>
		On the first day of Christmas<br />My good friends brought to me<br />A song for the Christmas
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

	<p style="font-style: italic;">(That was a silly song. Might want to go to the next day.)</p>
{:else if $page.params.day == '2'}
	<p>
		On the second day of Christmas<br />My good friends brought to me two hints<br />And a song for
		the Christmas tree
	</p>
	<img alt="Gift location uno" width="400px" src="/images/gift_location_uno.jpg" />
	<p style="font-style: italic;">(There are more days!)</p>
{:else if $page.params.day == '3'}
	<p>
		On the third day of Christmas<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree
	</p>
{:else if $page.params.day == '4'}
	<p>
		On the fourth day of Christmas<br />
		My good friends brought to me<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '5'}
	<p>
		On the fifth day of Christmas<br />
		My good friends brought to me<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '6'}
	<p>
		On the sixth day of Christmas<br />
		My good friends brought to me<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '7'}
	<p>
		On the seventh day of Christmas<br />
		My good friends brought to me<br />
		Candles a glowing<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '8'}
	<p>
		On the eighth day of Christmas<br />
		My good friends brought to me<br />
		Gold and silver tinsel<br />
		Candles a glowing<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '9'}
	<p>
		On the ninth day of Christmas<br />
		My good friends brought to me<br />
		A guardian angel<br />
		Gold and silver tinsel<br />
		Candles a glowing<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '10'}
	<p>
		On the tenth day of Christmas<br />
		My good friends brought to me<br />
		Some mistletoe<br />
		A guardian angel<br />
		Gold and silver tinsel<br />
		Candles a glowing<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '11'}
	<p>
		On the eleventh day of Christmas<br />
		My good friends brought to me<br />
		Gifts for one and all<br />
		Some mistletoe<br />
		A guardian angel<br />
		Gold and silver tinsel<br />
		Candles a glowing<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{:else if $page.params.day == '12'}
	<p>
		On the twefth day of Christmas<br />
		My good friends brought to me<br />
		All their good wishes<br />
		Gifts for one and all<br />
		Some mistletoe<br />
		A guardian angel<br />
		Gold and silver tinsel<br />
		Candles a glowing<br />
		Little silver bells<br />
		A shining star<br />
		Four colored lights<br />
		Three boughs of holly<br />
		Two hints<br />
		And a song for the Christmas tree<br />
	</p>
{/if}
