<script>
  let currentEmoji = "😊";
  setTimeout(function () {
    currentEmoji = "😢";
  }, 3000);
</script>

<style>
  div {
    font-size: 3em;
    margin-bottom: 0.5em;
  }
</style>

<div>{currentEmoji}</div>
