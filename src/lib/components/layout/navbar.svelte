<script lang="ts">
  import { fade } from "svelte/transition"
  import LogoLarge from "../svg/logo-large.svelte"
  import Button from "../ui/button/button.svelte"

  import MegaMenu from "./mega-menu/mega-menu.svelte"

  const MENU_ITEMS = ["Solutions", "Create", "Learn", "Company"]

  let activeMenuItem: string | null = null

  function handleMenuItemClick(value: string) {
    if (activeMenuItem === value) {
      activeMenuItem = null
    } else {
      activeMenuItem = value
    }
  }
</script>

<nav class="bg-white shadow-sm relative z-50">
  <div class="container mx-auto">
    <div class="flex items-center justify-between md:px-6 py-3 xl:py-0">
      <!-- Left side content -->
      <div class="flex items-center">
        <a href="/" class="mr-24">
          <LogoLarge />
        </a>

        <!-- Desktop menu -->
        <div class="items-center justify-between hidden xl:flex">
          <ul class="flex text-primary/90 gap-2">
            {#each MENU_ITEMS as link}
              <li>
                <a
                  href="/"
                  on:click={() => handleMenuItemClick(link)}
                  class="py-7 px-4 flex items-center gap-2 hover:text-secondary duration-100 border-t-2 border-transparent hover:border-secondary"
                >
                  <span>{link}</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke-width="2"
                    stroke="currentColor"
                    class="w-3 h-3"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="m19.5 8.25-7.5 7.5-7.5-7.5"
                    />
                  </svg>
                </a>
              </li>
            {/each}
            <li>
              <a
                href="/"
                class="py-7 px-4 flex items-center gap-2 hover:text-secondary duration-100 border-t-2 border-transparent hover:border-secondary"
              >
                <span>Partners</span>
              </a>
            </li>
          </ul>
        </div>
      </div>

      <!-- Get started button -->
      <div class="hidden xl:block">
        <ul class="flex items-center gap-4">
          <li
            class="flex justify-center items-center h-full text-primary/90 hover:text-secondary duration-100"
          >
            <a href="/" class="block py-2 px-3" aria-current="page">Pricing</a>
          </li>
          <li>
            <Button variant="secondary">Sign In</Button>
          </li>
          <li
            class="flex justify-center items-center h-full text-primary/90 hover:text-secondary duration-100"
          >
            <a href="/" class="block py-2 px-3" aria-current="page">English</a>
          </li>
        </ul>
      </div>

      <!-- Mobile menu button -->
      <button
        data-collapse-toggle="navbar-sticky"
        type="button"
        class="block xl:hidden"
        aria-controls="navbar-sticky"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
    </div>
  </div>
  {#if activeMenuItem}
    <div transition:fade>
      <MegaMenu />
    </div>
  {/if}
</nav>

{#if activeMenuItem}
  <!-- Backdrop blur -->
  <!-- svelte-ignore a11y-no-static-element-interactions -->
  <!-- svelte-ignore a11y-click-events-have-key-events -->
  <div
    transition:fade
    on:click={() => (activeMenuItem = null)}
    class="backdrop-blur-sm bg-black/55 fixed top-0 left-0 right-0 bottom-0 z-10"
  ></div>
{/if}
