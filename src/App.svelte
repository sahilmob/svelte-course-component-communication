<script>
  import Product from "./Product.svelte";
</script>

<Product
  productTitle="A book"
  on:add-to-cart={$event => console.log($event)}
  on:delete={() => console.log('delete')} />
