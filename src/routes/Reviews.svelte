<div class="all">
	<div class="title">
		<h4>THOUSANDS OF DRIVERS AND MILLIONS OF MILES</h4>
		<br /><br /><br /><br /><br /><br /><br />
		<h4>WE'VE BEEN FEATURED IN</h4>
	</div>

	<div class="articles">
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/engadget.png?alt=media&token=2425ab62-7b82-4c81-adf9-64d652080ce1" alt="engadget logo" class="engadget" />
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/consumer-reports.png?alt=media&token=676b62d3-e5fe-43d6-b711-18fa832dd7a5" alt="consumer reports logo" class="consumerReports" />
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/car-and-driver.png?alt=media&token=7e2dac4d-c07d-4b64-9e42-0938b6e9369e" alt="car and driver logo" class="carAndDriver" />
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/road-show.png?alt=media&token=c049e1a8-509c-4fad-86d2-a80f7fb3b337" alt="road show logo" class="roadShow" />
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/reason.png?alt=media&token=a026df98-372a-49ac-a5ab-a91d5efce50f" alt="reason logo" class="reason" />
		<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/the-drive.png?alt=media&token=3a5cd88d-43a4-4ee9-b75f-23b4d8e229c6" alt="the drive logo" class="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/the-drive.png?alt=media&token=3a5cd88d-43a4-4ee9-b75f-23b4d8e229c6" />
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
	h4 {
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
