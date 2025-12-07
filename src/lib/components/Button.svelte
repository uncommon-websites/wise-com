<script>
  export let text = "";
  export let href = "#";
  export let variant = "primary"; // primary, secondary, outline, text
  export let className = "";
</script>

{#if variant === 'primary'}
  <a {href} class="inline-flex items-center justify-center px-6 py-3 rounded-full bg-wise-green text-wise-dark font-semibold hover:bg-[#8fd663] transition-colors {className}">
    {text}
    <slot />
  </a>
{:else if variant === 'dark'}
  <a {href} class="inline-flex items-center justify-center px-6 py-3 rounded-full bg-wise-dark text-white font-semibold hover:bg-wise-dark-hover transition-colors {className}">
    {text}
    <slot />
  </a>
{:else if variant === 'outline'}
  <a {href} class="inline-flex items-center justify-center px-6 py-3 rounded-full border border-gray-300 text-wise-dark font-semibold hover:bg-gray-50 transition-colors {className}">
    {text}
    <slot />
  </a>
{:else}
  <a {href} class="inline-flex items-center justify-center px-4 py-2 text-wise-dark font-semibold hover:text-gray-600 transition-colors {className}">
    {text}
    <slot />
  </a>
{/if}
