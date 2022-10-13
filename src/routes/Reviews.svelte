<div class="all">
  <div class="title">
    <h4>THOUSANDS OF DRIVERS AND MILLIONS OF MILES</h4>
    <br><br><br><br><br><br><br>
    <h4>WE'VE BEEN FEATURED IN</h4>
  </div>
  
  <div class="articles">
    <img src="engadget.png" alt="engadget logo" class="engadget">
    <img src="consumer-reports.png" alt="consumer reports logo" class="consumerReports">
    <img src="car-and-driver.png" alt="car and driver logo" class="carAndDriver">
    <img src="road-show.png" alt="road show logo" class="roadShow">
    <img src="reason.png" alt="reason logo" class="reason">
    <img src="the-drive.png" alt="the drive logo" class="theDrive">
  </div>
</div>

<style>
  .title {
    padding: 50px;
    background-color: white;
    color: black;
    text-align: center;
  }
  h4 {
    display: inline-block;
    background: #86ff4e;
    padding: .5px;
  }
  .articles {
    width: 100%;
    padding: 40px;
  }
  .all {
    background-color: white;
  }
	@media screen and (min-width: 100px) {
		.articles {
      background-color: white;
      /* border: 3px solid red; */
      font-size: 20px;
			margin: auto;
			width: 100%;
			/* max-width: 1100px; */
			grid-template-columns: 1fr 1fr;
			grid-template-rows: 1fr;
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

	@media screen and (min-width: 800px) {
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
	}
</style>