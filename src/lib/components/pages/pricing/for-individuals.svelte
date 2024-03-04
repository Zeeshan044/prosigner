<script>
  import PricingCardSolo from "../../ui/cards/pricing-card-solo.svelte"
</script>

<section class="py-5 w-full max-w-7xl mx-auto px-12 text-primary">
  <div class="px-4">
    <div class="text-center">
      <h3 class="text-2xl font-semibold mb-2 mt-3 font-geo">For individuals</h3>
      <p class="mb-4 text-lg font-mulish leading-snug">
        Turn your emails into powerful marketing tools with a professionally
        designed email signature.
      </p>
    </div>
    <div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 py-5">
        <!-- first card -->
        <PricingCardSolo />
        <PricingCardSolo />
      </div>
    </div>
  </div>
</section>
