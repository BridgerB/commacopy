<div class="all">
<div class="blackBox">
	<h1>openpilot</h1>
	<br />
	<p>
		openpilot is open source software built to improve upon the existing driver assistance in most
		new cars on the road today. Tesla Autopilot like functionality for your Toyota, Honda, and other
		top brands. See what Consumer Reports thinks of it.
	</p>
	<br />
	<p>View on GitHub ></p>
	<p>See it in action ></p>
</div>
<div class="background">
	<div class="eyes">
		<h1>Keep your eyes on the road.</h1>
		<br />
		<p>
			While engaged, openpilot includes camera based driver monitoring that works both day and night
			to alert the driver when their eyes are not on the road ahead.
		</p>
		<br />
		<p style="color:green;">See driver monitoring in action ></p>
		<br />
		<img class="bbb" src="driver-monitoring-at-night.jpg" alt="example of internal camera" />
	</div>
</div>
</div>


<style>
	* {
		margin: 0;
		padding: 0;
		background-color: black;
	}
	.blackBox {
		margin: 0;
		padding: 100px;
		background-color: black;
		height: 100px;
	}
	p,
	h1 {
		text-align: center;
		max-width: 934px;
		width: 80%;
		margin: 0 auto;

		display: block;
		color: white;
	}
	.bbb {
		width: 60%;
	}
	.eyes {
		transform: translate(0,900px);
		max-width: 1240px;
		width: 80%;
		background-color: black;
		border: 3px solid white;
		margin: auto;
		color: white;
		/* padding: 90px; */
	}
	.background {
		height: 1000px;
		width: 100%;
		background: 
			linear-gradient(180deg, rgb(0, 0, 0) 0%, rgba(255,255,255,0) 50%, rgb(0, 0, 0) 100%),
			url('/openpilot-cover-three.jpg');
		background-repeat: no-repeat;
		background-position: center;
		background-size: cover;
		margin-bottom: 700px;
	}
	.all {
		background-color: black;
		padding-bottom: 100px;
	}
</style>
