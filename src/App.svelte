<script>
  import { onMount, onDestroy } from 'svelte'
  import Navbar from './components/Navbar.svelte'
  // * Import any other components needed here

  onMount(() => {
    console.log('App mounted')
  })
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }
  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <Navbar />
  <h1>Svelte TypeScript BoilerPlate!</h1>
  <h3>Start building your app by adding to src/App.svelte</h3>
</main>
