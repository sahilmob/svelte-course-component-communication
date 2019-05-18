<script>
  import Product from "./Product.svelte";
</script>

<Product productTitle="A book" on:click={() => console.log('clicked')} />
