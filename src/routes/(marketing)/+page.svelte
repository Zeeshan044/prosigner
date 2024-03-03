<script>
  import Hero from "../../lib/components/layout/hero.svelte"
  import PricingCards from "../../lib/components/layout/pricing-cards.svelte"
  import ForIndividuals from "../../lib/components/layout/for-individuals.svelte"
  import WhyUs from "../../lib/components/layout/why-us.svelte"
  import FeaturesList from "../../lib/components/layout/features-list.svelte"
</script>

<!-- <section class="container mx-auto mt-12">
  <h1 class="text-5xl font-bold text-center font-geo">
    WiseStamp Plans and Pricing
  </h1>
  <p class="text-center mt-6 text-lg2">
    Effortlessly create and manage your team’s email signatures.
  </p>
</section> -->

<section>
  <Hero />
  <PricingCards />
  <FeaturesList />
  <ForIndividuals />
  <WhyUs />
</section>
