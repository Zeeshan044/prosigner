<script>
  import PricingCardSolo from "../../ui/cards/pricing-card-solo.svelte"
</script>

<section class="py-5 w-full max-w-7xl mx-auto px-4 md:px-12 text-primary">
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
        <PricingCardSolo
          title="Solo Free"
          price="$0"
          features={[
            "One free email signature",
            "Basic layouts",
            "Basic design customization",
            "WiseStamp branding on signature",
          ]}
          description="Create a free signature for yourself in just a few clicks."
        />
        <PricingCardSolo
          title="Solo Pro"
          price="$5.8"
          features={[
            "Premium Templates",
            "Advanced style & design",
            "Unlimited signatures",
            "Remove WiseStamp branding",
            "Add animations and effects",
            "Export to iPhone, Outlook, and more",
          ]}
          description="Create a stunning and professional email signature with Solo Pro."
        />
      </div>
    </div>
  </div>
</section>
