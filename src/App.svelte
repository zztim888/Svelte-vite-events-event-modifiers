<script>
  function handleClick(){
    alert('you have clicked!')
  }
</script>

<button on:click={handleClick}>
  Click me! on:click
</button>

<!-- two modifiers are chained together "click|once" -->
<button on:click|once={handleClick}>
  Click me! on:click|once
</button>

<!-- <button on:click={handleClick}> -->
<!-- three modifiers are chained together "click|once|capture" -->
<button on:click|once|capture={handleClick}>
  Click me! on:click|once|capture
</button>