<script>
  import { MaterialApp, Button } from "svelte-materialify";
  import AppBar from "./AppBar.svelte";
  import colors from "svelte-materialify/src/utils/colors";
  import Button1 from "./Button.svelte";
  const theme = "light";
</script>



<style>
  div {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 40vh;
  }
  h1 {
    text-align: center;
    font-weight: 700;
  }
</style>

<MaterialApp {theme}>
	<AppBar />
  <div>
  <h1>Svelte Material app</h1>
  </div>
  <div>
  <Button1 />
  </div>
</MaterialApp>