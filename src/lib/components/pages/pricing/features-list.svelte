<script>
  import {
    ADMIN_SECURITY,
    CONTROL_EFFICIENCY,
    ESSENTIAL_FEATURES,
    PERFORMANCE,
    SUPPORT,
  } from "$lib/data/pricing/features"
  import { cn } from "$lib/utils"
  import CheckCircle from "../../svg/check-circle.svelte"

  let hidden = true

  function toggleHidden() {
    hidden = !hidden
  }
</script>

<section class="pb-8 pt-24">
  <div class="ws-container">
    <div class="flex justify-center">
      <button
        on:click={toggleHidden}
        class="flex justify-center items-center gap-4"
      >
        <h5 class="text-2xl font-bold cursor-pointer">
          Complete features list
        </h5>
        <svg
          width="18"
          height="18"
          viewBox="0 0 12 7"
          class="dropdown-trigger-icon transition-transform duration-300 ease-in-out cursor-pointer"
          style="transform: rotate({!hidden ? '180deg' : '0deg'})"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          ><path
            d="M5.60156 5.89844L1.10156 1.39844C0.867188 1.1875 0.867188 0.835938 1.10156 0.601562C1.3125 0.390625 1.66406 0.390625 1.89844 0.601562L6 4.72656L10.1016 0.625C10.3125 0.390625 10.6641 0.390625 10.8984 0.625C11.1094 0.835938 11.1094 1.1875 10.8984 1.39844L6.375 5.89844C6.16406 6.13281 5.8125 6.13281 5.60156 5.89844Z"
            fill="currentColor"
          ></path></svg
        >
      </button>
    </div>
    <div class="mt-8">
      <table id="features-table" class={cn("w-full", hidden ? "hidden" : null)}>
        <thead>
          <tr>
            <th
              class="font-bold tracking-wider border-b border-gray-300 uppercase text-secondary w-1/3 p-4 text-left h-16"
              >Essential Features</th
            >
            <td
              class="h-16 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Basic</td
            >
            <td
              class="h-16 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Plus</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Enterprise</td
            >
          </tr>
        </thead>
        <tbody>
          {#each ESSENTIAL_FEATURES as feature}
            <tr>
              <th
                class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
                >{feature.title}</th
              >
              <td class="w-1/4 p-4">
                {#if feature?.basic}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.plus}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.enterprise}
                  <CheckCircle />
                {/if}
              </td>
            </tr>
          {/each}
        </tbody>

        <thead>
          <tr>
            <th
              class="font-bold tracking-wider border-b border-gray-300 uppercase text-secondary w-1/3 p-4 text-left h-16"
              >Control &amp; Efficiency</th
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Basic</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Plus</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Enterprise</td
            >
          </tr>
        </thead>
        <tbody>
          {#each CONTROL_EFFICIENCY as feature}
            <tr>
              <th
                class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
                >{feature.title}</th
              >
              <td class="w-1/4 p-4">
                {#if feature?.basic}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.plus}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.enterprise}
                  <CheckCircle />
                {/if}
              </td>
            </tr>
          {/each}
        </tbody>

        <thead>
          <tr>
            <th
              class="font-bold tracking-wider border-b border-gray-300 uppercase text-secondary w-1/3 p-4 text-left h-16"
              >Performance</th
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Basic</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Plus</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Enterprise</td
            >
          </tr>
        </thead>
        <tbody>
          {#each PERFORMANCE as feature}
            <tr>
              <th
                class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
                >{feature.title}</th
              >
              <td class="w-1/4 p-4">
                {#if feature?.basic}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.plus}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.enterprise}
                  <CheckCircle />
                {/if}
              </td>
            </tr>
          {/each}
        </tbody>

        <thead>
          <tr>
            <th
              class="font-bold tracking-wider border-b border-gray-300 uppercase text-secondary w-1/3 p-4 text-left h-16"
              >Admin &amp; Security</th
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Basic</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Plus</td
            >
            <td
              class="h-4 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Enterprise</td
            >
          </tr>
        </thead>
        <tbody>
          {#each ADMIN_SECURITY as feature}
            <tr>
              <th
                class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
                >{feature.title}</th
              >
              <td class="w-1/4 p-4">
                {#if feature?.basic}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.plus}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.enterprise}
                  <CheckCircle />
                {/if}
              </td>
            </tr>
          {/each}
        </tbody>

        <thead>
          <tr>
            <th
              class="font-bold tracking-wider border-b border-gray-300 uppercase text-secondary w-1/3 p-4 text-left h-16"
              >Support</th
            >
            <td
              class="h-16 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Basic</td
            >
            <td
              class="h-16 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Plus</td
            >
            <td
              class="h-16 w-1/4 p-4 text-center border-b border-gray-300 text-base font-bold leading-6"
              >Enterprise</td
            >
          </tr>
        </thead>
        <tbody>
          {#each SUPPORT as feature}
            <tr>
              <th
                class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
                >{feature.title}</th
              >
              <td class="w-1/4 p-4">
                {#if feature?.basic}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.plus}
                  <CheckCircle />
                {/if}
              </td>
              <td class="w-1/4 p-4">
                {#if feature?.enterprise}
                  <CheckCircle />
                {/if}
              </td>
            </tr>
          {/each}
        </tbody>
      </table>
    </div>
  </div>
</section>
