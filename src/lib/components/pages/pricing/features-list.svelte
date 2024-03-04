<script>
  import { cn } from "$lib/utils"
  import FeaturedTableTick from "../../ui/featured-table-tick.svelte"

  // let rotated = false
  let hidden = true

  function toggleHidden() {
    // const table = document.getElementById("features-table")
    // rotated = !rotated
    // // @ts-ignore
    // if (table.classList.contains("hidden")) {
    //   // @ts-ignore
    //   table.classList.remove("hidden")
    // } else {
    //   // @ts-ignore
    //   table.classList.add("hidden")
    // }

    hidden = !hidden
  }
</script>

<section class="py-8">
  <div class="max-w-7xl px-12 mx-auto">
    <div class="">
      <div class="dropdown-trigger flex justify-center items-center gap-4">
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <!-- svelte-ignore a11y-no-noninteractive-element-interactions -->
        <h5 class="text-2xl font-bold cursor-pointer" on:click={toggleHidden}>
          Complete features list
        </h5>
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <!-- svelte-ignore a11y-no-static-element-interactions -->
        <svg
          width="18"
          height="11"
          on:click={toggleHidden}
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
      </div>
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
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Centrally managed</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Unlimited signature designs</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Pre-built signature templates</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Sync with your directory</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Instantly deploy signature updates</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Supports all devices</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Supports all email clients</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Flexible deployment options</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Legal disclaimers</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
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
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Department specific signatures</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Signature data customization</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Employee signature portal</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >CRM support</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Custom directory sync</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Employee lifecycle automation</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Supports shared inbox</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Details editable by employee</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Multiple organizational domains</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
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
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Specialized design elements</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Promotional banners</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Signature analytics</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Campaigns</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Multiple signatures per employee</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Signature rules like reply &amp; internal</th
            >
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
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
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Roles &amp; permissions</th
            >
            <td> </td>
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >SAML single sign-in</th
            >
            <td> </td>
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >User provisioning through SCIM</th
            >
            <td> </td>
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >External access control
            </th>
            <td> </td>
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Audit log</th
            >
            <td> </td>
            <td> </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
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
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Email support</th
            >
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
            <td class="w-1/4 p-4">
              <FeaturedTableTick />
            </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Dedicated onboarding specialist</th
            >
            <td> </td>
            <td class=" text-center"> for 50+ seats </td>
            <td class=" text-center"> for 50+ seats </td>
          </tr>
          <tr>
            <th
              class="w-1/3 h-4 p-4 text-left font-normal text-primary font-mulish"
              >Dedicated customer success manager</th
            >
            <td> </td>
            <td> </td>
            <td class=" text-center"> for 200+ seats </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</section>
