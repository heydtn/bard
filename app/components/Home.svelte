<script lang="ts">
  let message: string = "Blank Svelte Native App";
</script>

<page actionBarHidden="false">
  <actionBar title="Hello Borski!" />
  <dockLayout stretchLastChild="false" backgroundColor="#3c495e">
    <flexboxLayout
      width="100%"
      dock="bottom"
      flexDirection="column"
      backgroundColor="#286290"
    >
      <label text="wow1" height="70" backgroundColor="#ff0000" />
      <label text="wow2" height="70" backgroundColor="#00ff00" />
    </flexboxLayout>
  </dockLayout>
</page>

<style>
  .info .fas {
    color: #3a53ff;
  }

  .info {
    font-size: 20;
    horizontal-align: center;
    vertical-align: center;
  }
</style>
