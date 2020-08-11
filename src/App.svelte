<script>
  import EmojiDisplay from "./EmojiDisplay.svelte";
</script>

<style>
  button {
    background-color: aqua;
    padding: 0.75em;
    border-radius: 0.25em;
    border: 2px solid #000;
    box-shadow: 0.4rem 0.4rem 0 #222;
  }
  button:hover {
    box-shadow: 0.25rem 0.25rem 0 #222;
    transition: all 0.4s ease 0s;
    background-color: aquamarine;
  }
  div {
    margin: 2em;
  }
</style>

<div>
  <h1>Randomize Emoji</h1>
  <EmojiDisplay />
  <button>✔ Randomize</button>
</div>
