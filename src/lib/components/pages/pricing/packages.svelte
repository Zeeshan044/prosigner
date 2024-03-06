<script>
  import {
    EMPLOYEES_COUNT,
    PRICING_FEATURES_1,
    PRICING_FEATURES_2,
    PRICING_FEATURES_3,
  } from "$lib/data/pricing/features"
  import PricingCard from "../../ui/cards/pricing-card.svelte"
</script>

<section class="bg-white">
  <div class="ws-container">
    <div class="my-12">
      <label for="" class=" flex">
        <span class="text-primary font-mulish py-1 font-semibold"
          >Choose team size</span
        >
        <div class=" ms-6 flex">
          <select
            class="relative w-full border border-gray-300 rounded-md py-1 px-2 font-semibold text-base leading-6 font-mulish text-primary"
            value="150"
          >
            {#each EMPLOYEES_COUNT as option}
              <option value={option.value}>{option.label}</option>
            {/each}
          </select>
        </div>
      </label>
    </div>
    <div class="grid md:grid-cols-2 xl:grid-cols-3 gap-6">
      <PricingCard
        packageName="Basic"
        featurePrice="$1.5"
        totalPrice="$225"
        description="Create professional and consistent signatures for your organization."
        featureList={PRICING_FEATURES_1}
      />
      <div class="mt-6 md:mt-0">
        <PricingCard
          packageName="Plus"
          featurePrice="$1.8"
          totalPrice="$270"
          description="Get advanced features & analytics for your signatures."
          featureList={PRICING_FEATURES_2}
          recommended
        />
      </div>
      <PricingCard
        packageName="Enterprise"
        featurePrice="$1.8"
        totalPrice="$270"
        description="Securely manage your signatures at the highest scale."
        featureList={PRICING_FEATURES_3}
        enterprise
      />
    </div>
  </div>
</section>
