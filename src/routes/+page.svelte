<script>
  import CommaThree from './CommaThree.svelte';
  import TwoEyesOutside from './TwoEyesOutside.svelte';
  import Openpilot from './Openpilot.svelte';
  import Compatibility from './Compatibility.svelte';
  import Reviews from './Reviews.svelte';


</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Archivo+Black&display=swap" rel="stylesheet">
</svelte:head>
<body>
	<div>
		<CommaThree />
	</div>
	<div>
    
		<TwoEyesOutside />
		<Openpilot />
		<Compatibility />
		<Reviews />
	</div>

</body>

<style>
	/* body {
    padding:0;
    margin:0;
  } */
	/* *, *::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
} */
</style>