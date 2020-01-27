<script>
  import Router from "./Router.svelte";
  import Route from "./Route.svelte";
</script>

<ul>
  <li>
    <a href="/">Home</a>
  </li>
  <li>
    <a href="/foo">Foo</a>
  </li>
  <li>
    <a href="/bar">Bar</a>
  </li>
</ul>

<Router hashbang={false}>
  <Route path="/">This is HOME page.</Route>
  <Route path="/foo">This is FOO page.</Route>
</Router>
