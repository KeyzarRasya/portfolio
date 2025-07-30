<script>
  export let src;
  export let href = "";
  export let alt = "";
  export let isLink = false;
  export let size = "10"; // ensure Tailwind has h-10, w-10 classes in safelist if dynamic
</script>

{#if isLink}
  <a href={href}>
    <img src={src} alt={alt} class={`h-${size} w-${size}`} />
  </a>
{:else}
  <img src={src} alt={alt} class={`h-${size} w-${size}`} />
{/if}
