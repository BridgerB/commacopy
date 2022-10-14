<div class="title2">
	<p class="about">
		Unlike many <u>OEM ADAS systems</u>, openpilot can <u>drive for hours</u> without intervention.
		We sell a devkit that can run openpilot with 360° HDR vision, <u>compatible</u> with 200+ cars.
		Starting at $1999.
		<a href="https://comma.ai/" style="color:#86ff4e; text-decoration: none;">Buy Now ></a>
		<br>
		<br>
	</p>
</div>
<hr />
<div class="three">
	<p class="install">
		<img src="/icon-fast-light-green.svg" width="75" alt="clock icon" /><br /> <br />
		<b>Easy to Install.</b> Watch our <u>step-by-step</u> videos. Install it yourself in as little as
		5 minutes.
	</p>
	<p class="trial">
		<img src="/icon-calendar-light-green.svg" width="55" alt="calender icon" /><br />
		<br />
		30 Day Money Back Trial. We think you'll love it, but if you're not satisfied, you can send it back
		for a <u>full refund</u>.
	</p>
	<p class="affirm">
		<img src="/icon-affirm-light-green.svg" width="50" alt="hourglass icon" /><br />
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
			/* text-align: center; */
			/* border: 3px solid white; */
		}
		.trial {
			grid-area: trial;
			margin: 50px;
			padding: 10px;
			/* border: 3px solid white; */
		}
		.affirm {
			grid-area: affirm;
			margin: 50px;
			padding: 10px;
			/* border: 3px solid white; */
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
			/* text-align: center; */
			/* border: 3px solid white; */
		}
		.trial {
			grid-area: trial;
			margin: 50px;
			padding: 10px;
			/* border: 3px solid white; */
		}
		.affirm {
			grid-area: affirm;
			margin: 50px;
			padding: 10px;
			/* border: 3px solid white; */
		}
	}
</style>
