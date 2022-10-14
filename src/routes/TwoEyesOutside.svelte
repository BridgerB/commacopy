<script>
	import { onMount } from 'svelte';

	// This was a (crappy) temp solution. needs fixed.
	let message = [`two eyes outside`, `one eye inside`, `comma three`];
	let x = 0;
	async function asyncCall() {
		while (1 < 2) {
			await new Promise((resolve) => setTimeout(resolve, 6800));
			x++;
			await new Promise((resolve) => setTimeout(resolve, 5000));
			x++;
			await new Promise((resolve) => setTimeout(resolve, 6163));
			x = 0;
		}
	}
	asyncCall();
	onMount(async () => {
		let vid = document.getElementById('video1');
		video1.onloadedmetadata = function () {
			console.log(this.duration);
		};
	});
</script>

<div id="videoDiv">
	<video id="video1" autoplay muted loop>
		<source src="/c3-hero.mp4" type="video/mp4" />
	</video>
	<div id="videoMessage" class="styling">
		<h1 class="message">{message[x]}</h1>
		<button><b>Buy Now</b></button>
	</div>
</div>

<style>
	.message {
		font-size: 80px;
	}
	#videoDiv {
		position: relative;
	}
	#video1 {
		display: block;
		width: 100%;
	}
	#videoMessage {
		position: absolute;
		top: 0;
		left: 0;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		width: 100%;
		height: 100%;
		color: white;
	}
	button {
		border: none;
		border-radius: 5px;
		padding-right: 80px;
		padding-left: 80px;
		padding-top: 25px;
		padding-bottom: 25px;
		font-size: 20px;
		background-color: #86ff4e;
	}
</style>
