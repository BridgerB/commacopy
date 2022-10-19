<div class="title2">
	<p class="about">
		Unlike many <u>OEM ADAS systems</u>, openpilot can <u>drive for hours</u> without intervention.
		We sell a devkit that can run openpilot with 360° HDR vision, <u>compatible</u> with 200+ cars.
		Starting at $1999.
		<a href="https://comma.ai/" style="color:#86ff4e; text-decoration: none;">Buy Now ></a>
		<br />
		<br />
	</p>
</div>
<hr />
<div class="three">
	<p class="install">
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/icon-fast-light-green.svg?alt=media&token=71435118-f71e-46e4-858b-f44aab5793f6" width="75" alt="clock icon" /><br /> <br />
		<b>Easy to Install.</b> Watch our <u>step-by-step</u> videos. Install it yourself in as little as
		5 minutes.
	</p>
	<p class="trial">
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/icon-calendar-light-green.svg?alt=media&token=d046c0eb-abe2-4ff2-9ff8-8343ba9b1250" width="55" alt="calender icon" /><br />
		<br />
		30 Day Money Back Trial. We think you'll love it, but if you're not satisfied, you can send it back
		for a <u>full refund</u>.
	</p>
	<p class="affirm">
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/icon-affirm-light-green.svg?alt=media&token=18786307-c34d-4139-831c-742418135fb0" width="50" alt="hourglass icon" /><br />
		<br />
		Pay over time. With Affirm, you can pay monthly for the comma three. <u>Learn more</u>.
	</p>
</div>

<style>
	* {
		background-color: #0f0f0f;
		margin: 0;
		padding: 0;
	}
	.about {
		margin: auto;
		padding-bottom: 50px;
		width: 80%;
		max-width: 1150px;
		font-size: 35px;
	}
	hr {
		margin: auto;
		padding: 0;
		width: 69%;
		max-width: 1150px;
	}

	@media screen and (min-width: 100px) {
		.three {
			font-size: 20px;
			margin: auto;
			width: 100%;
			max-width: 1100px;
			grid-template-columns: 1fr 1fr 1fr;
			grid-template-rows: 1fr 1fr;
			grid-template-areas:
				'install'
				'trial'
				'affirm';
		}
		.install {
			margin: 50px;
			padding: 10px;
			grid-area: install;
		}
		.trial {
			grid-area: trial;
			margin: 50px;
			padding: 10px;
		}
		.affirm {
			grid-area: affirm;
			margin: 50px;
			padding: 10px;
		}
	}

	@media screen and (min-width: 900px) {
		.three {
			max-width: 1270px;
			display: grid;
			grid-template-columns: 1fr 1fr 1fr;
			grid-template-rows: 1fr 1fr;
			grid-template-areas: 'install trial affirm';
		}

		.install {
			margin: 50px;
			padding: 10px;
			grid-area: install;
		}
		.trial {
			grid-area: trial;
			margin: 50px;
			padding: 10px;
		}
		.affirm {
			grid-area: affirm;
			margin: 50px;
			padding: 10px;
		}
	}
</style>
