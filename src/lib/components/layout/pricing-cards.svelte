<script>
  import PricingCardTick from "../ui/pricing-card-tick.svelte"
  import PricingCardTooltip from "../ui/pricing-card-tooltip.svelte"

  let options = [
    { value: "1", label: "1 employee" },
    { value: "5", label: "5 employees" },
    { value: "10", label: "10 employees" },
    { value: "20", label: "20 employees" },
    { value: "30", label: "30 employees" },
    { value: "40", label: "40 employees" },
    { value: "50", label: "50 employees" },
    { value: "60", label: "60 employees" },
    { value: "70", label: "70 employees" },
    { value: "80", label: "80 employees" },
    { value: "90", label: "90 employees" },
    { value: "100", label: "100 employees" },
    { value: "125", label: "125 employees" },
    { value: "150", label: "150 employees" },
    { value: "175", label: "175 employees" },
    { value: "200", label: "200 employees" },
    { value: "201+", label: "201+ employees" },
  ]
</script>

<section class="bg-white">
  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6">
    <div class=" my-12">
      <label for="" class=" flex">
        <span class="text-primary font-mulish py-1 font-semibold"
          >Choose team size</span
        >
        <div class=" ms-6 flex">
          <select
            class="relative w-full border border-gray-300 rounded-md py-1 px-2 font-semibold text-base leading-6 font-mulish text-primary"
            value="150"
          >
            {#each options as option}
              <option value={option.value}>{option.label}</option>
            {/each}
          </select>
        </div>
      </label>
    </div>
    <div
      class="space-y-8 lg:grid lg:grid-cols-3 sm:gap-6 xl:gap-10 lg:space-y-0"
    >
      <!-- Pricing Card first -->
      <div
        class="flex flex-col p-6 mx-auto max-w-lg text-center text-primary shadow-lg bg-white rounded-lg border border-gray-100"
      >
        <h3 class="mb-2 text-2xl text-start font-bold">Basic</h3>
        <div class="flex justify-start items-center my-2">
          <span class="mr-2 text-4xl font-semibold">$29</span>
          <span class="block">seat/month</span>
        </div>

        <div class="mt-2">
          <h3 class="mr-2 text-lg font-bold text-start">Total $225 / month</h3>
          <h6 class="text-start">Billed annually</h6>
        </div>

        <p class="text-start my-4 font-bold">
          Create professional and consistent signatures for your organization.
        </p>

        <a
          href="#"
          class="text-white bg-secondary hover:bg-secondary font-mulish rounded-lg px-5 py-3 my-4 text-center"
          >Try for Free</a
        >

        <!-- List -->
        <ul role="list" class="mb-8 space-y-4 text-left">
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Centrally managed</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Unlimited designs</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Compatible with all devices</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Department signatures</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Works with all email clients</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Flexible deployment</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <PricingCardTick />
              <span class="text-sm">Legal disclaimers</span>
            </div>
            <div>
              <PricingCardTooltip />
            </div>
          </li>
        </ul>
      </div>

      <!-- Pricing Card second -->

      <div
        class="flex flex-col p-6 mx-auto max-w-lg text-center text-primary bg-white rounded-lg border border-gray-100 shadow-lg"
      >
        <h3 class="mb-2 text-2xl text-start font-bold">plus</h3>
        <div class="flex justify-start items-center my-2">
          <span class="mr-2 text-4xl font-semibold">$29</span>
          <span class="block">seat/month</span>
        </div>

        <div class="mt-2">
          <h3 class="mr-2 text-lg font-bold text-start">Total $270 / month</h3>
          <h6 class="text-start">Billed annually</h6>
        </div>

        <p class="text-start my-4 font-bold">
          Create professional and consistent signatures for your organization.
        </p>

        <a
          href="#"
          class="text-white bg-secondary hover:bg-darkpink rounded-lg font-mulish px-5 py-3 my-4 text-center"
          >Try for Free</a
        >

        <!-- List -->
        <ul role="list" class="mb-8 space-y-4 text-left">
          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">Individual configuration</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">No setup, or hidden fees</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm"
                >Team size: <span class="font-semibold">1 developer</span></span
              >
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm"
                >Premium support: <span class="font-semibold">6 months</span
                ></span
              >
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm"
                >Free updates: <span class="font-semibold">6 months</span></span
              >
            </div>
            <div><PricingCardTooltip /></div>
          </li>
        </ul>
      </div>

      <!-- Pricing Card third -->
      <div
        class="flex flex-col p-6 mx-auto max-w-lg w-full text-center text-primary bg-white rounded-lg border border-gray-100 shadow-lg"
      >
        <h3 class="mb-2 text-2xl text-start font-bold">Enterprise</h3>

        <div class="my-4">
          <svg
            width="73"
            height="72"
            viewBox="0 0 73 72"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            ><path
              d="M29.8239 46.4014L19.3204 57.0362C17.8553 58.5196 17.1228 59.2613 16.4931 59.3136C15.9468 59.359 15.412 59.1394 15.0552 58.7232C14.644 58.2435 14.644 57.2011 14.644 55.1161V49.7882C14.644 47.9177 13.1122 46.5643 11.2614 46.2932V46.2932C6.78215 45.637 3.26431 42.1192 2.60819 37.6399C2.5 36.9013 2.5 36.02 2.5 34.2574V18.3943C2.5 12.6558 2.5 9.78651 3.6168 7.59467C4.59916 5.66667 6.16667 4.09916 8.09467 3.1168C10.2865 2 13.1558 2 18.8943 2H44.169C49.9075 2 52.7768 2 54.9686 3.1168C56.8966 4.09916 58.4641 5.66667 59.4465 7.59467C60.5633 9.78651 60.5633 12.6558 60.5633 18.3943V32.7394M60.5633 70.3098L53.1298 65.1417C52.0849 64.4153 51.5624 64.052 50.9938 63.7945C50.4891 63.5659 49.9585 63.3996 49.4137 63.2992C48.7998 63.186 48.1635 63.186 46.8908 63.186H40.7535C36.9278 63.186 35.0149 63.186 33.5537 62.4415C32.2684 61.7866 31.2234 60.7416 30.5684 59.4563C29.8239 57.995 29.8239 56.0822 29.8239 52.2565V43.669C29.8239 39.8433 29.8239 37.9304 30.5684 36.4692C31.2234 35.1838 32.2684 34.1388 33.5537 33.4839C35.0149 32.7394 36.9278 32.7394 40.7535 32.7394H59.8802C63.7059 32.7394 65.6188 32.7394 67.08 33.4839C68.3653 34.1388 69.4103 35.1838 70.0652 36.4692C70.8098 37.9304 70.8098 39.8433 70.8098 43.669V52.9396C70.8098 56.1224 70.8098 57.7138 70.2898 58.9692C69.5965 60.6429 68.2667 61.9728 66.5929 62.6661C65.3376 63.186 63.7461 63.186 60.5633 63.186V70.3098Z"
              stroke="#08415C"
              stroke-width="3.07394"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path></svg
          >
        </div>

        <p class="text-start my-4 pt-3 font-bold">
          Create professional and consistent signatures for your organization.
        </p>

        <a
          href="#"
          class="  text-secondary hover:bg-secondary hover:text-white border-2 border-secondary rounded-lg font-mulish px-5 py-3 my-4 text-center"
          >Contact Sales</a
        >

        <!-- List -->
        <ul
          role="list"
          class="mb-8 space-y-4 text-left font-mulish text-primary"
        >
          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">SAML single sign in</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>
          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">SCIM like Okta</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">External access control</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">Dedicated CSM</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>

          <li class="flex items-center justify-between">
            <div class="flex space-x-3">
              <PricingCardTick />
              <span class="text-sm">Audit log</span>
            </div>
            <div><PricingCardTooltip /></div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</section>
