<div class="all">
	<hr />
	<br />
	<div class="grid">
		<div class="header">
			<h3>Try the comma three with our 30-day money back trial.</h3>
		</div>

		<div class="right">
			<button class="button"><b>Buy Now</b></button>
			<br />
			<br />
			<br />
			<p class="affirm">Starting at $181/mo with <b>Affirm</b>. Learn more</p>
		</div>
	</div>
</div>

<style>
	.all {
		padding: 50px;
		margin: 0px;
		background-color: #232323;
	}
	hr {
		width: 80%;
		max-width: 1200px;
	}
	@media screen and (min-width: 100px) {
		.grid {
			margin: auto;
			width: 80%;
			display: grid;
			grid-template-columns: 1fr 1fr;
			grid-template-rows: 1fr;
			grid-template-areas:
				'header'
				'right';
		}
		.header {
			grid-area: header;
			font-size: 35px;
		}
		.button {
			grid-area: button;
			float: right;
			color: black;
			background-color: #86ff4e;
			border-radius: 4px;
			padding-left: 70px;
			padding-right: 70px;
			padding-top: 15px;
			padding-bottom: 15px;
			font-size: 18px;
			border: none;
		}
		.affirm {
			grid-area: affirm;
			float: right;
			font-size: 17px;
		}
		.right {
			grid-area: right;
			float: right;
		}
	}
	@media screen and (min-width: 500px) {
		.grid {
			width: 80%;
			max-width: 1200px;
			display: grid;
			grid-template-columns: 1fr 1fr;
			grid-template-rows: 1fr;
			grid-template-areas: 'header right';
		}
	}
</style>
