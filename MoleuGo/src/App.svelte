<script>
  import Router from 'svelte-spa-router';
  import Index from "./routes/Index.svelte";
  import MainPage from './routes/MainPage.svelte';
  import SignupPage from './routes/SignupPage.svelte';
  import FindPassword from './routes/FindPassword.svelte';

  const routes = {
    '/': Index,
    '/main' : MainPage,
    '/signup': SignupPage,
    '/findpassword' : FindPassword
  };
</script>

<Router {routes}/>

