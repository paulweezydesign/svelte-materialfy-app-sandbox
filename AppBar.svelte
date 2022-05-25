<script>
  import { MaterialApp, AppBar, Button, Icon } from "svelte-materialify";
  import { mdiMenu, mdiDotsVertical } from "@mdi/js";
  let collapsed=false
</script>


  <AppBar {collapsed} class="primary-color theme--dark">
  <div slot="icon">
    <Button fab depressed text>
      <Icon path={mdiMenu} />
    </Button>
  </div>
  <span slot="title">Cloud Kickstarter</span>
<div style="flex-grow:1" />
<Button>Login</Button>
  </AppBar>

