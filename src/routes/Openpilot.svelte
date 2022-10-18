<div class="all">
	<div class="blackBox">
		<h1>openpilot</h1>
		<br />
		<p>
			openpilot is open source software built to improve upon the existing driver assistance in most
			new cars on the road today. Tesla Autopilot like functionality for your Toyota, Honda, and
			other top brands. See what <u>Consumer Reports</u> thinks of it.
		</p>
		<br />
		<p>View on GitHub ></p>
		<p>See it in action ></p>
	</div>
	<div class="background">
		<div class="eyes">
			<br />
			<br />
			<h1>Keep your eyes on the road.</h1>
			<br />
			<p>
				While engaged, openpilot includes camera based driver monitoring that works both day and
				night to alert the driver when their eyes are not on the road ahead.
			</p>
			<br />
			<p style="color:#79eb4c;">See driver monitoring in action ></p>
			<br />
			<img
				class="monitoring"
				src="driver-monitoring-at-night.jpg"
				alt="example of internal camera"
			/>
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
		padding-bottom: 150px;
		background-color: black;
		height: 100px;
		width: 65%;
		margin: auto;
		font-size: 25px;
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
	.monitoring {
		width: 60%;
		display: block;
		margin-left: auto;
		margin-right: auto;
		padding: 30px;
	}
	.eyes {
		transform: translate(0, 900px);
		max-width: 1430px;
		width: 90%;
		background-color: black;
		border: 1.5px solid white;
		margin: auto;
		color: white;
		font-size: 26px;
	}
	.background {
		height: 1000px;
		width: 100%;
		background: linear-gradient(
				180deg,
				rgb(0, 0, 0) 0%,
				rgba(255, 255, 255, 0) 50%,
				rgb(0, 0, 0) 100%
			),
			url('https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/openpilot-cover-three.jpg?alt=media&token=38546e0c-d169-498a-b253-eb60a5d8f5e5');
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
