<div class="all">
	<div class="grid">
		<img class="comma" src="comma-white.png" alt="github logo" width="24px" />
		<br />
		<div class="product">
			<b><p>Product</p></b>
			<p>comma three</p>
			<p>openpilot</p>
			<p>prime</p>
			<p>Shop</p>
			<p>Compatibility</p>
		</div>
		<br />
		<div class="information">
			<b><p>Information</p></b>
			<p>Setup Guide</p>
			<p>Support & FAQ</p>
			<p>Shipping / Returns</p>
			<p>Discord</p>
			<p>Wiki</p>
		</div>
		<br />
		<div class="company">
			<b><p>Company</p></b>
			<p>Jobs</p>
			<p>Blog</p>
		</div>
		<br />
		<div class="email">
			<b><p>Get the latest updates from comma</p></b>
			<br />
			<input type="text" placeholder="your@email.com" />
			<br />
			<br />
			<img src="icon-github-white.png" alt="github logo" width="24px" />
			<img src="icon-instagram-white.png" alt="instagram logo" width="24px" />
			<img src="icon-twitter-white.png" alt="twitter logo" width="24px" />
			<img src="icon-youtube-white.png" alt="youtube logo" width="24px" />
		</div>
	</div>
	<br />
</div>

<style>
	@media screen and (min-width: 100px) {
		.grid {
			margin: auto;
			width: 80%;
			display: grid;
			grid-template-columns: 1fr;
			grid-template-rows: 1fr 1fr 1fr 1fr 1fr;
			grid-template-areas:
				'comma'
				'product'
				'information'
				'company'
				'email';
		}
	}
	@media screen and (min-width: 860px) {
		.grid {
			width: 80%;
			max-width: 1000px;
			display: grid;
			grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
			grid-template-rows: 1fr;
			grid-template-areas: 'comma product information company email';
		}
	}
	img {
		margin: auto;
		padding: 6px;
	}
	input {
		background-color: black;
		color: white;
	}
	.all {
		font-size: 22px;
		padding: 40px;
	}

	.comma {
		grid-area: comma;
	}

	.product {
		grid-area: product;
	}
	.information {
		grid-area: information;
	}
	.company {
		grid-area: company;
	}
	.email {
		grid-area: email;
	}
	p {
		padding: 0;
		margin: 8px;
	}
</style>
