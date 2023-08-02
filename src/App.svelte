<script>
  import Main from "./Components/Main.svelte";
  import Login from "./Components/Login.svelte";
  import SignUp from "./Components/SignUp.svelte";
  import PocketBase from 'pocketbase';
  
  const pb = new PocketBase('http://127.0.0.1:8090');
</script>

<main>
  <Login />
  <SignUp />
</main>

<style>
</style>
