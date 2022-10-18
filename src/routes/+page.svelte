<script>
	import { onMount } from 'svelte';
	import CommaCopy from './CommaCopy.svelte';
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


	import { initializeApp } from 'firebase/app';
	import { getAnalytics } from 'firebase/analytics';
	const firebaseConfig = {
		apiKey: 'AIzaSyDk_-UKrGpvM3ovj2RV95UfVTEcxIo08_4',
		authDomain: 'commacopy.firebaseapp.com',
		projectId: 'commacopy',
		storageBucket: 'commacopy.appspot.com',
		messagingSenderId: '239626345124',
		appId: '1:239626345124:web:4de6e1fa27c5d53a786431',
		measurementId: 'G-XQS4TS6B20'
	};
	onMount(() => {
		const app = initializeApp(firebaseConfig);
		const analytics = getAnalytics(app);
	});


</script>

<svelte:head>
	<title>Comma Copy</title>
	<meta name="commacopy" content="comma.ai redone in SvelteKit" />
</svelte:head>

<body>
	<div>
		<CommaCopy />
		<NavBar />
		<!-- <SideBar /> -->
		<GreenBar />
		<Title1 />
		<CommaThree />
		<br /><br />
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
		padding: 0;
		margin: 0;
		background-color: #0f0f0f;
		color: white;
	}
</style>
