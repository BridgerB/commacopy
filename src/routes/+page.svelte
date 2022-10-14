<script>
  import Title1 from './Title1.svelte';
  import CommaThree from './CommaThree.svelte';
	import Title2 from './Title2.svelte';
  import TwoEyesOutside from './TwoEyesOutside.svelte';
  import Openpilot from './Openpilot.svelte';
  import Compatibility from './Compatibility.svelte';
  import Reviews from './Reviews.svelte';
  import Trial from './Trial.svelte';
  import GreenBar from './GreenBar.svelte';
  import NavBar from './NavBar.svelte';
  import SideBar from './SideBar.svelte';

  import Footer from './Footer.svelte';
  import Footer2 from './Footer2.svelte';
  import Twitter from './Twitter.svelte';



</script>

<!-- <svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Archivo+Black&display=swap" rel="stylesheet">
</svelte:head> -->

<body>	
	<div>
		<NavBar />
		<!-- <SideBar /> -->
		<GreenBar />
		<Title1 />
    <CommaThree />
		<Title2 />
		<TwoEyesOutside />
		<Openpilot />
		<Compatibility />
		<Reviews />
		<Trial />
		<Footer />
		<Footer2 />

		<!-- <Twitter /> -->

	</div>

</body>

<style>
	body {
    padding:0;
    margin:0;
		background-color: #0f0f0f;
		color: white;
  }
	/* *, *::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>