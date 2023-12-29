<script>
	import References from './../lib/references.svelte';
	import Features from './../lib/features.svelte';
      import Hero from "$lib/hero.svelte";
      import Snippets from "$lib/snippets.svelte";
  import Access from '$lib/access.svelte';
  import Supercharge from '$lib/supercharge.svelte';
  import Footer from '$lib/footer.svelte';
  import Cta from '$lib/CTA.svelte';

</script>

<Hero/>
<Snippets/>
<Features/>
<Access/>
<Supercharge/>
<References/>
<Cta/>
<Footer/>
<slot/>