<script>
  import { Router, Link } from 'svelte-move';
  import { routes } from './routes';
</script>

<style>
</style>

<main>
  Welcome to your Electron Template
  <div>
    <Link to="/">Home</Link>
    <Router {routes} hash={true} />
  </div>
</main>
