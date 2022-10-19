<div class="all">
	<div class="title">
		<p><b>THOUSANDS OF DRIVERS AND MILLIONS OF MILES</b></p>
		<br /><br /><br /><br /><br /><br /><br />
		<p><b>WE'VE BEEN FEATURED IN</b></p>
	</div>

	<div class="articles">
		<img
			src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Fengadget.webp?alt=media&token=30b3b5e8-ebfc-4717-8161-ae3d085ca350"
			alt="engadget logo"
			class="engadget"
			width="224"
			height="48"
		/>
		<img
			src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Fconsumer-reports.webp?alt=media&token=3a8f90c8-55de-40ff-9f57-642fcfc9ace0"
			alt="consumer reports logo"
			class="consumerReports"
			width="204"
			height="48"
		/>
		<img
			src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Fcar-and-driver.webp?alt=media&token=dea6795b-753c-4c02-b478-a791057c2351"
			alt="car and driver logo"
			class="carAndDriver"
			width="232"
			height="40"
		/>
		<img
			src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Froad-show.webp?alt=media&token=0901a5dc-7d97-483e-adf1-12f98a9731c3"
			alt="road show logo"
			class="roadShow"
			width="306"
			height="48"
		/>
		<img
			src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Freason.webp?alt=media&token=328e9c5d-203e-48e8-9e60-34cc638bdd81"
			alt="reason logo"
			class="reason"
			width="239"
			height="48"
		/>
		<img
			src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Fthe-drive.webp?alt=media&token=a9e2b047-4b87-468a-8308-4c85d7a9ed1b"
			alt="the drive logo"
			class="theDrive"
			width="360"
			height="48"
		/>
	</div>
</div>

<style>
	.title {
		padding: 50px;
		background-color: white;
		color: black;
		text-align: center;
		font-size: 35px;
	}
	p {
		display: inline-block;
		background: #86ff4e;
		padding: 0.5px;
	}
	.articles {
		width: 100%;
		padding: 0px;
	}
	.all {
		background-color: white;
		padding-bottom: 150px;
	}
	@media screen and (min-width: 100px) {
		.articles {
			text-align: center;
			background-color: white;
			font-size: 20px;
			margin: auto;
			width: 100%;
			grid-template-columns: 1fr;
			grid-template-rows: auto;
			grid-template-areas:
				'engadget'
				'consumerReports'
				'carAndDriver'
				'roadShow'
				'reason'
				'theDrive';
		}
		.engadget {
			padding: 20px;
			grid-area: engadget;
		}
		.consumerReports {
			padding: 20px;
			grid-area: consumerReports;
		}
		.carAndDriver {
			padding: 20px;
			grid-area: carAndDriver;
		}
		.roadShow {
			padding: 20px;
			grid-area: roadShow;
		}
		.reason {
			padding: 20px;
			grid-area: reason;
		}
		.theDrive {
			padding: 20px;
			grid-area: theDrive;
		}
	}

	/* @media screen and (min-width: 400px) {
		.articles {
			display: grid;
			grid-template-columns: auto;
			grid-template-rows: auto;
			grid-template-areas:
				'engadget consumerReports carAndDriver'
				'roadShow reason theDrive';
		}
	}
	@media screen and (min-width: 1500px) {
		.articles {
			width: 100%;
			max-width: 1800px;
			display: grid;
			grid-template-columns: auto;
			grid-template-rows: auto;
			grid-template-areas: 'engadget consumerReports carAndDriver roadShow reason theDrive';
		}
	} */
</style>
