

<svelte:head>
	<title>Tobi</title>
</svelte:head>

<div class="column">
	<a href="/pic4zoom"><img src="/assets/images/thumbs/pic4thumb.webp" alt="fuckit"></a>
	<a href="/pic5zoom"><img src="/assets/images/thumbs/pic5thumb.webp" alt="fuckit"></a>
	<a href="/pic7zoom"><img src="/assets/images/thumbs/pic7thumb.webp" alt="fuckit"></a>
	<a href="/pic8zoom"><img src="/assets/images/thumbs/pic8thumb.webp" alt="fuckit"></a>
	<a href="/pic9zoom"><img src="/assets/images/thumbs/pic9thumb.webp" alt="fuckit"></a>
	<a href="/pic10zoom"><img src="/assets/images/thumbs/pic10thumb.webp" alt="fuckit"></a>
	<a href="/pic12zoom"><img src="/assets/images/thumbs/pic12thumb.webp" alt="fuckit"></a>
	
	
	<a href="/pic1_1zoom"><img src="/assets/images/thumbs/pic1_1thumb.webp" alt="fuckit"></a>
	<a href="/pic2_1zoom"><img src="/assets/images/thumbs/pic2_1thumb.webp" alt="fuckit"></a>
	<a href="/pic3_1zoom"><img src="/assets/images/thumbs/pic3_1thumb.webp" alt="fuckit"></a>
	<a href="/p1zoom"><img src="/assets/images/thumbs/p1thumb.webp" alt="fuckit"></a>
	<a href="/p2zoom"><img src="/assets/images/thumbs/p2thumb.webp" alt="fuckit"></a>
	<a href="/p3zoom"><img src="/assets/images/thumbs/p3thumb.webp" alt="fuckit"></a>
	<a href="/p4zoom"><img src="/assets/images/thumbs/p4thumb.webp" alt="fuckit"></a>
	<a href="/p5zoom"><img src="/assets/images/thumbs/p5thumb.webp" alt="fuckit"></a>
	<a href="/pic13zoom"><img src="/assets/images/thumbs/FB_IMG_1thumb.webp" alt="fuckit"></a>
	<a href="/pic14zoom"><img src="/assets/images/thumbs/FB_IMG_2thumb.webp" alt="fuckit"></a>
	<a href="/pic15zoom"><img src="/assets/images/thumbs/FB_IMG_3thumb.webp" alt="fuckit"></a>
	<a href="/pic16zoom"><img src="/assets/images/thumbs/FB_IMG_4thumb.webp" alt="fuckit"></a>
</div>
<a href="https://frontpage-czi.pages.dev/" ><button>Home</button></a>
<style>

	button {
        width: 25%;
		padding: 8px;
		border-radius: 7px;
		background-color: white;
		font-size: 1.25em;
		color: black;
		text-align: center;
    }

	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		border-radius: 10%;
		max-width: 225px;
	}

	@media screen and (max-width: 420px) {
		img {
			width: 120px;
		}
	}

	@media screen and (max-width: 360px) {
		img {
			width: 100px;
		}
	}
</style>
