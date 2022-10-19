<div class="all">
	<div class="grid">
		<img class="comma" src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Fcomma-white.webp?alt=media&token=620b2780-0c3c-4429-95ae-936d0f4478d2" alt="github logo" width="24px" height="43px" />
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
			<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Ficon-github-white.webp?alt=media&token=aa98de78-7665-46c1-94d2-ae66412e60f5" alt="github logo" width="24px" height="24"/>
			<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Ficon-instagram-white.webp?alt=media&token=e9fe71ca-26f3-4ab1-a2f0-0575ea3bbcae" alt="instagram logo" width="24px" height="24" />
			<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Ficon-twitter-white.webp?alt=media&token=d6eb8366-009a-40d2-8e5e-1b4cfd3d77e1" alt="twitter logo" width="24px" height="24" />
			<img src="https://firebasestorage.googleapis.com/v0/b/commacopy.appspot.com/o/webpFiles%2Ficon-youtube-white.webp?alt=media&token=041b219c-b48d-4884-9910-54037ba43953" alt="youtube logo" width="24px" height="24"/>
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
