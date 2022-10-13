<div class="title2">
	<p class="about">
		Unlike many <u>OEM ADAS systems</u>, openpilot can <u>drive for hours</u> without intervention.
		We sell a devkit that can run openpilot with 360° HDR vision, <u>compatible</u> with 200+ cars.
		Starting at $1999. <a href="url" style="color:#86ff4e; text-decoration: none;">Buy Now ></a>
	</p>
</div>
<hr />
<div class="three">
	<p class="install">
		<img src="icon-fast-light-green.svg" width="72" height="55" /><br />
		<b>Easy to Install.</b> Watch our <u>step-by-step</u> videos. Install it yourself in as little as 5 minutes.
	</p>
	<p class="trial">
		<img src="icon-calendar-light-green.svg" width="72" height="55" /><br />
		30 Day Money Back Trial. We think you'll love it, but if you're not satisfied, you can send it back
		for a <u>full refund</u>.
	</p>
	<p class="affirm">
		<img src="icon-affirm-light-green.svg" width="72" height="55" /><br />
		Pay over time. With Affirm, you can pay monthly for the comma three. <u>Learn more</u>.
	</p>
</div>

<!-- @media screen and (min-width: 800px) {
    
  	.site {
			display: grid;
			grid-template-columns: 1fr 1fr;
      grid-template-rows: auto 1fr 3fr;
      grid-template-areas:
        "content-head content-head"
        "main header"
        "main sidebar"
        "footer footer";
		}
    
    .masthead {
      grid-area: header;
    }
    
    .page-title {
      grid-area: content-head;
    }
    
    .main-content {
      grid-area: main;
    }
    
    .sidebar {
      grid-area: sidebar;
    }
		
    .colophon {
      grid-area: footer;
    }
    
	}
  
  @media screen and (min-width: 1200px) {
    .site {
			grid-template-columns: 2fr 1fr 1fr;
      grid-template-areas:
        "content-head content-head content-head"
        "main header header"
        "main sidebar footer";
		}
  } -->
<style>
  *{ 
    background-color: #0f0f0f;
    margin: 0;
    padding: 0;
  }
	.about {
		margin: auto;
		padding-bottom: 50px;
		width: 80%;
		max-width: 1100px;
		font-size: 35px;
	}
	hr {
		margin: auto;
    padding: 0;
		width: 80%;
		max-width: 1100px;
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
