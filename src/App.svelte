<script>
  function handleClick(){
    alert('you have clicked!')
  }
</script>

<h1>Chain together modifiers</h1>
<button on:click={handleClick}>
  Click me! on:click
</button><br><br>

<!-- two modifiers are chained together "click|once" -->
<button on:click|once={handleClick}>
  Click me! on:click|once
</button><br><br>

<!-- <button on:click={handleClick}> -->
<!-- three modifiers are chained together "click|once|capture" -->
<button on:click|once|capture={handleClick}>
  Click me! on:click|once|capture
</button>