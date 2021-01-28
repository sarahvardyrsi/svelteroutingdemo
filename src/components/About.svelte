<script>
  import { Link } from 'svelte-routing';
</script>

<div>
  <h3>This is About Page.</h3>
  <Link to="/">Home</Link><br />
  <Link to="chat">Chat</Link><br />
  <Link to="clock">Clock</Link>
</div>
<div class="aboutBody">
  <p>This is a demo with some super sweet code taken from the online examples and embedded in components.</p>
</div>