<script lang="ts">
  import Check from "$lib/components/svg/check.svelte"
  import Info from "$lib/components/svg/info.svelte"

  export let featureList: string[] = []
  export let packageName: string
  export let featurePrice: string
  export let totalPrice: string
  export let description: string
  export let recommended: boolean = false
  export let enterprise: boolean = false
</script>

<div
  class={`shadow-custom bg-white rounded-lg relative ${recommended && "rounded-tr-none rounded-tl-none"}`}
>
  {#if recommended}
    <div
      class="bg-[#33cc9d] text-white text-center font-bold text-sm uppercase py-2 absolute left-0 bottom-full right-0 rounded-tr-lg rounded-tl-lg"
    >
      Best Value
    </div>
  {/if}
  <div class="p-8 flex flex-col">
    <h3 class="mb-2 text-3xl text-start font-medium font-geo">
      {packageName}
    </h3>

    {#if enterprise}
      <div class="py-7">
        <svg
          width="60"
          height="60"
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
    {:else}
      <div class="flex justify-start items-center my-2">
        <span class="mr-2 text-4xl font-bold">{featurePrice}</span>
        <span class="block leading-none ml-2">seat/<br />month</span>
      </div>

      <div class="mt-2">
        <h3 class="mr-2 text-lg font-bold text-start">
          Total {totalPrice} / month
        </h3>
        <h6 class="text-start">Billed annually</h6>
      </div>
    {/if}

    <p class="text-start my-4 font-bold">
      {description}
    </p>

    {#if enterprise}
      <a
        href="/"
        class="text-secondary text-lg bg-white hover:bg-secondary duration-100 border-2 border-secondary hover:text-white font-mulish rounded px-5 py-2 my-4 text-center font-semibold"
        >Contact Sales</a
      >
    {:else}
      <a
        href="/"
        class="text-white text-lg bg-secondary hover:bg-secondary-dark duration-100 font-mulish border border-secondary rounded px-5 py-2 my-4 text-center"
        >Try for Free</a
      >
    {/if}

    <!-- List -->
    <ul role="list" class="mb-8 space-y-4 text-left">
      {#each featureList as feature}
        <li class="flex items-center justify-between">
          <div class="flex items-center space-x-3">
            <Check className="fill-green-500 h-5 w-5" />
            <span class="text-sm">{feature}</span>
          </div>
          <div>
            <Info className="fill-gray-400 h-3 w-3" />
          </div>
        </li>
      {/each}
    </ul>
  </div>
</div>
