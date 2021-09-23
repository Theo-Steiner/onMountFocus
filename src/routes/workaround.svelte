<script>
  const focusAndScroll = (node) => {
    setTimeout(() => node.focus(), 0);
    setTimeout(() => node.scrollIntoView(), 0);
  };
</script>

<div>They see me (sc)rollin'...</div>
<div style="background-color: peru;">
  <label for="input">Focus! </label>
  <input use:focusAndScroll id="input" type="text" />
</div>
<div style="background-color: teal;">They focusin'</div>

<style>
  div {
    background-color: hotpink;
    height: 80vh;
  }
</style>
