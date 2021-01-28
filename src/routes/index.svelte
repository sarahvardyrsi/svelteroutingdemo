<script>
  import { Router, Route } from 'svelte-routing';
  import Home from '../components/Home.svelte';
  import About from '../components/About.svelte';
  import Chat from '../components/Chat.svelte';
  import Clock from '../components/Clock.svelte';

  export let url = '';
</script>

<Router {url}>
  <div>
    <Route path="chat" component={Chat} />
    <Route path="about" component={About} />
    <Route path="clock" component={Clock} />
    <Route path="/" component={Home} />
  </div>
</Router>