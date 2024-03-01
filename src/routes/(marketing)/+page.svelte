<script lang="ts">
  const features = [
    {
      name: "Signature Templates",
      link: "/login",
      description: "Beatiful ready to use signature templates.",
      svgContent: `<path
                  d="M14.2084 13.5521C16.3025 13.5521 18 11.8615 18 9.77606C18 7.6906 16.3025 6 14.2084 6C12.1144 6 10.4169 7.6906 10.4169 9.77606C10.4169 10.742 10.8578 11.4446 10.8578 11.4446L6.27264 16.011C6.0669 16.2159 5.77886 16.7486 6.27264 17.2404L6.8017 17.7673C7.00743 17.9429 7.52471 18.1888 7.94796 17.7673L8.56519 17.1526C9.18242 17.7673 9.88782 17.416 10.1523 17.0647C10.5932 16.45 10.0642 15.8353 10.0642 15.8353L10.2405 15.6597C11.087 16.5027 11.8277 16.011 12.0922 15.6597C12.5331 15.045 12.0922 14.4303 12.0922 14.4303C11.9159 14.079 11.5632 14.079 12.004 13.64L12.5331 13.113C12.9564 13.4643 13.8264 13.5521 14.2084 13.5521Z"
                  stroke="#1C274C"
                  stroke-width="1.5"
                  stroke-linejoin="round"
                />
                <path
                  d="M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8"
                  stroke="#1C274C"
                  stroke-width="1.5"
                  stroke-linecap="round"
                />`,
    },
    {
      name: "Central Managment",
      link: "/pricing",
      description: "Manage your companies signatures from one location.",
      svgContent: `<path d="M12 6V18" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M15 9.5C15 8.11929 13.6569 7 12 7C10.3431 7 9 8.11929 9 9.5C9 10.8807 10.3431 12 12 12C13.6569 12 15 13.1193 15 14.5C15 15.8807 13.6569 17 12 17C10.3431 17 9 15.8807 9 14.5" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>`,
    },
    {
      name: "Easy to Use",
      link: "/blog",
      description: "Your are up and running in no time with ProSigner.",
      svgContent: `<path d="M20.965 7C20.8873 5.1277 20.6366 3.97975 19.8284 3.17157C18.6569 2 16.7712 2 13 2H11C7.22876 2 5.34315 2 4.17157 3.17157C3 4.34315 3 6.22876 3 10V14C3 17.7712 3 19.6569 4.17157 20.8284C5.34315 22 7.22876 22 11 22H13C16.7712 22 18.6569 22 19.8284 20.8284C21 19.6569 21 17.7712 21 14V11" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M6 12C6 10.5858 6 9.87868 6.43934 9.43934C6.87868 9 7.58579 9 9 9H15C16.4142 9 17.1213 9 17.5607 9.43934C18 9.87868 18 10.5858 18 12V16C18 17.4142 18 18.1213 17.5607 18.5607C17.1213 19 16.4142 19 15 19H9C7.58579 19 6.87868 19 6.43934 18.5607C6 18.1213 6 17.4142 6 16V12Z" stroke="#1C274C" stroke-width="1.5"/>
<path d="M7 6H12" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>`,
    },
    {
      name: "Subscriptions",
      link: "/pricing",
      description: "User friendly subscriptions powered by Stripe Checkout.",
      svgContent: `<path d="M10 16.5H6" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M8 13.5H6" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M14 15C14 14.0572 14 13.5858 14.2929 13.2929C14.5858 13 15.0572 13 16 13C16.9428 13 17.4142 13 17.7071 13.2929C18 13.5858 18 14.0572 18 15C18 15.9428 18 16.4142 17.7071 16.7071C17.4142 17 16.9428 17 16 17C15.0572 17 14.5858 17 14.2929 16.7071C14 16.4142 14 15.9428 14 15Z" stroke="#1C274C" stroke-width="1.5"/>
<path d="M22 12C22 8.22876 22 6.34315 20.8284 5.17157C19.6569 4 17.7712 4 14 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H14C17.7712 20 19.6569 20 20.8284 18.8284C21.4816 18.1752 21.7706 17.3001 21.8985 16" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M2 10L7 10M22 10L11 10" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>`,
    },
    {
      name: "Billing Portal",
      link: "/account/billing",
      description:
        "Self-serve portal for changing card, receipts, upgrades, downgrades and more.",
      svgContent: `<path d="M21 6V3.50519C21 2.92196 20.3109 2.61251 19.875 2.99999C19.2334 3.57029 18.2666 3.57029 17.625 2.99999C16.9834 2.42969 16.0166 2.42969 15.375 2.99999C14.7334 3.57029 13.7666 3.57029 13.125 2.99999C12.4834 2.42969 11.5166 2.42969 10.875 2.99999C10.2334 3.57029 9.26659 3.57029 8.625 2.99999C7.98341 2.42969 7.01659 2.42969 6.375 2.99999C5.73341 3.57029 4.76659 3.57029 4.125 2.99999C3.68909 2.61251 3 2.92196 3 3.50519V14M21 10V20.495C21 21.0782 20.3109 21.3876 19.875 21.0002C19.2334 20.4299 18.2666 20.4299 17.625 21.0002C16.9834 21.5705 16.0166 21.5705 15.375 21.0002C14.7334 20.4299 13.7666 20.4299 13.125 21.0002C12.4834 21.5705 11.5166 21.5705 10.875 21.0002C10.2334 20.4299 9.26659 20.4299 8.625 21.0002C7.98341 21.5705 7.01659 21.5705 6.375 21.0002C5.73341 20.4299 4.76659 20.4299 4.125 21.0002C3.68909 21.3876 3 21.0782 3 20.495V18" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M7.5 15.5H11.5M16.5 15.5H14.5" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M16.5 12H12.5M7.5 12H9.5" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>
<path d="M7.5 8.5H16.5" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>`,
    },
    {
      name: "User Dashboard",
      link: "/account/settings",
      description:
        "User profile, user settings, update email/password, billing, and more.",
      svgContent: `<circle cx="12" cy="12" r="3" stroke="#1C274C" stroke-width="1.5"/>
<path d="M3.66122 10.6392C4.13377 10.9361 4.43782 11.4419 4.43782 11.9999C4.43781 12.558 4.13376 13.0638 3.66122 13.3607C3.33966 13.5627 3.13248 13.7242 2.98508 13.9163C2.66217 14.3372 2.51966 14.869 2.5889 15.3949C2.64082 15.7893 2.87379 16.1928 3.33973 16.9999C3.80568 17.8069 4.03865 18.2104 4.35426 18.4526C4.77508 18.7755 5.30694 18.918 5.83284 18.8488C6.07287 18.8172 6.31628 18.7185 6.65196 18.5411C7.14544 18.2803 7.73558 18.2699 8.21895 18.549C8.70227 18.8281 8.98827 19.3443 9.00912 19.902C9.02332 20.2815 9.05958 20.5417 9.15224 20.7654C9.35523 21.2554 9.74458 21.6448 10.2346 21.8478C10.6022 22 11.0681 22 12 22C12.9319 22 13.3978 22 13.7654 21.8478C14.2554 21.6448 14.6448 21.2554 14.8478 20.7654C14.9404 20.5417 14.9767 20.2815 14.9909 19.9021C15.0117 19.3443 15.2977 18.8281 15.7811 18.549C16.2644 18.27 16.8545 18.2804 17.3479 18.5412C17.6837 18.7186 17.9271 18.8173 18.1671 18.8489C18.693 18.9182 19.2249 18.7756 19.6457 18.4527C19.9613 18.2106 20.1943 17.807 20.6603 17C20.8677 16.6407 21.029 16.3614 21.1486 16.1272M20.3387 13.3608C19.8662 13.0639 19.5622 12.5581 19.5621 12.0001C19.5621 11.442 19.8662 10.9361 20.3387 10.6392C20.6603 10.4372 20.8674 10.2757 21.0148 10.0836C21.3377 9.66278 21.4802 9.13092 21.411 8.60502C21.3591 8.2106 21.1261 7.80708 20.6601 7.00005C20.1942 6.19301 19.9612 5.7895 19.6456 5.54732C19.2248 5.22441 18.6929 5.0819 18.167 5.15113C17.927 5.18274 17.6836 5.2814 17.3479 5.45883C16.8544 5.71964 16.2643 5.73004 15.781 5.45096C15.2977 5.1719 15.0117 4.6557 14.9909 4.09803C14.9767 3.71852 14.9404 3.45835 14.8478 3.23463C14.6448 2.74458 14.2554 2.35523 13.7654 2.15224C13.3978 2 12.9319 2 12 2C11.0681 2 10.6022 2 10.2346 2.15224C9.74458 2.35523 9.35523 2.74458 9.15224 3.23463C9.05958 3.45833 9.02332 3.71848 9.00912 4.09794C8.98826 4.65566 8.70225 5.17191 8.21891 5.45096C7.73557 5.73002 7.14548 5.71959 6.65205 5.4588C6.31633 5.28136 6.0729 5.18269 5.83285 5.15108C5.30695 5.08185 4.77509 5.22436 4.35427 5.54727C4.03866 5.78945 3.80569 6.19297 3.33974 7C3.13231 7.35929 2.97105 7.63859 2.85138 7.87273" stroke="#1C274C" stroke-width="1.5" stroke-linecap="round"/>`,
    },
  ]

  import { PUBLIC_SITE_NAME } from "$env/static/public"
</script>

<svelte:head>
  <title>{PUBLIC_SITE_NAME}</title>
  <meta name="description" content="{PUBLIC_SITE_NAME} Home Page" />
</svelte:head>

<div class="hero min-h-[60vh]">
  <div class="hero-content text-center py-12">
    <div class="max-w-xl">
      <div
        class="text-xl md:text-3xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-primary to-accent mb-4"
      >
        ProSigner
      </div>

      <div class="text-4xl md:text-6xl font-bold px-2">
        Transform Your
        <span
          class="underline decoration-secondary decoration-4 md:decoration-[6px]"
          >Email Signature</span
        >, into a
        <span
          class="underline decoration-secondary decoration-4 md:decoration-[6px]"
          >Marketing Tool</span
        >
      </div>
      <div class="mt-4 text-sm md:text-lg">
        Works great with <a
          href="https://kit.svelte.dev"
          class="link font-bold"
          target="_blank">Gmail</a
        >,
        <a href="https://supabase.com" class="link font-bold" target="_blank"
          >Google Workspace</a
        >,
        <a href="https://stripe.com" class="link font-bold" target="_blank"
          >Outlook desktop</a
        >,
        <a href="https://tailwindcss.com" class="link font-bold" target="_blank"
          >Outlook web</a
        >,
        <a href="https://tailwindcss.com" class="link font-bold" target="_blank"
          >iPhone</a
        >,
        <a href="https://daisyui.com" class="link font-bold" target="_blank"
          >iPhone</a
        >, and
        <a
          href="https://www.postgresql.org"
          class="link font-bold"
          target="_blank">Yahoo Mail</a
        >
      </div>

      <div class="mt-6">
        <a href="/pricing">
          <button class="btn btn-primary btn-sm px-6">Get Started</button>
        </a>
        <a
          href="https://github.com/CriticalMoments/CMSaasStarter/tree/main#saas-starter"
        >
          <button class="btn btn-outline btn-primary btn-sm px-6 mt-3 mx-2"
            >Read more</button
          >
        </a>
      </div>
    </div>
  </div>
</div>
<div>
  <img src="images/logos/apple.svg" alt="Prosign" />
</div>
<div class="companies-section py-12">
  <div class="text-center mb-8">
    <h2 class="text-3xl font-bold">Trusted by Leading Companies</h2>
  </div>
  <div class="w-full inline-flex flex-nowrap">
    <ul
      class="flex items-center justify-center md:justify-start [&_li]:mx-8 [&_img]:max-w-none animate-infinite-scroll"
    >
      <li>
        <img src="images/logos/facebook.svg" alt="Facebook" />
      </li>
      <li>
        <img src="images/logos/disney.svg" alt="Disney" />
      </li>
      <li>
        <img src="images/logos/airbnb.svg" alt="Airbnb" />
      </li>
      <li>
        <img src="images/logos/apple.svg" alt="Apple" />
      </li>
      <li>
        <img src="images/logos/spark.svg" alt="Spark" />
      </li>
      <li>
        <img src="images/logos/samsung.svg" alt="Samsung" />
      </li>
      <li>
        <img src="images/logos/quora.svg" alt="Quora" />
      </li>
      <li>
        <img src="images/logos/sass.svg" alt="Sass" />
      </li>
    </ul>
    <ul
      class="flex items-center justify-center md:justify-start [&_li]:mx-8 [&_img]:max-w-none animate-infinite-scroll"
      aria-hidden="true"
    >
      <li>
        <img src="images/logos/facebook.svg" alt="Facebook" />
      </li>
      <li>
        <img src="images/logos/disney.svg" alt="Disney" />
      </li>
      <li>
        <img src="images/logos/airbnb.svg" alt="Airbnb" />
      </li>
      <li>
        <img src="images/logos/apple.svg" alt="Apple" />
      </li>
      <li>
        <img src="images/logos/spark.svg" alt="Spark" />
      </li>
      <li>
        <img src="images/logos/samsung.svg" alt="Samsung" />
      </li>
      <li>
        <img src="images/logos/quora.svg" alt="Quora" />
      </li>
      <li>
        <img src="images/logos/sass.svg" alt="Sass" />
      </li>
    </ul>
  </div>
</div>

<div class="min-h-[60vh]">
  <div class="pt-20 pb-8 px-7">
    <div class="max-w-lg mx-auto text-center">
      <div
        class="text-3xl md:text-5xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-primary to-accent"
      >
        Explore the Features
      </div>
      <div class="mt-6 text-xl font-bold">
        And try them on this
        <span
          class="underline decoration-secondary decoration-[3px] md:decoration-[4px]"
        >
          fully functional demo
        </span>
      </div>
    </div>

    <div
      class="flex gap-6 mt-12 max-w-[1064px] mx-auto place-content-center flex-wrap"
    >
      {#each features as feature}
        <div
          class="card bg-white w-[270px] md:w-[300px] min-h-[300px] flex-none shadow-xl"
        >
          <div class="card-body items-center text-center p-[24px] pt-[32px]">
            <div>
              <svg
                width="50px"
                height="50px"
                class="mb-2 mt-1"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                {@html feature.svgContent}
              </svg>
            </div>
            <h2 class="card-title">
              {feature.name}
            </h2>
            <p class="text-sm">
              {feature.description}
            </p>
            {#if feature.link}
              <a
                href={feature.link}
                class="pb-4"
                target={feature.newPage ? "_blank" : ""}
              >
                <button
                  class="btn btn-xs btn-outline rounded-full btn-primary min-w-[100px]"
                  >{feature.linkText ? feature.linkText : "Try It"}</button
                >
              </a>
            {/if}
          </div>
        </div>
      {/each}
    </div>
  </div>
</div>
<div class="container mx-auto px-4 py-8">
  <div class="max-w-lg mx-auto text-center">
    <div
      class="text-3xl md:text-5xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-primary to-accent"
    >
      Seamless Integration
    </div>
    <div class="mt-6 text-xl font-bold">
      Be up and running in
      <span
        class="underline decoration-secondary decoration-[3px] md:decoration-[4px]"
      >
        almost no time.
      </span>
    </div>
  </div>

  <div
    class="flex gap-6 mt-12 max-w-[1064px] mx-auto place-content-center flex-wrap"
  >
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Google Workspace -->
      <div class="p-4 border border-gray-200 rounded-lg">
        <img
          src="images/logos/Google-workspace-icon.svg"
          alt=""
          class="mb-4 max-w-full h-auto"
        />
        <h3 class="text-lg font-semibold mb-2">
          Google Workspace Signature Management
        </h3>
        <p class="mb-2">
          Effortless one-click synchronization for all employees through API
          integration.
        </p>
        <p class="mb-2">Automatic updates reflecting employee changes.</p>
        <p class="mb-4">
          User-specific access control for editable signature fields.
        </p>
        <div class="mt-6">
          <a href="/pricing">
            <button class="btn btn-primary btn-sm px-6">Get Started</button>
          </a>
          <a
            href="https://github.com/CriticalMoments/CMSaasStarter/tree/main#saas-starter"
          >
            <button class="btn btn-outline btn-primary btn-sm px-6 mt-3 mx-2"
              >Read more</button
            >
          </a>
        </div>
      </div>

      <!-- Office 365 -->
      <div class="p-4 border border-gray-200 rounded-lg">
        <img
          src="images/logos/outlook-office-logo.svg"
          alt=""
          class="mb-4 max-w-full h-auto"
        />

        <h3 class="text-lg font-semibold mb-2">
          Office 365 Signature Management
        </h3>
        <p class="mb-2">
          Hassle-free integration for Outlook 2019+, Mac v16.56+, with no need
          for third-party servers.
        </p>

        <p class="mb-4">
          Company-wide deployment and synchronization of signatures on all
          devices.
        </p>
        <div class="mt-6">
          <a href="/pricing">
            <button class="btn btn-primary btn-sm px-6">Get Started</button>
          </a>
          <a
            href="https://github.com/CriticalMoments/CMSaasStarter/tree/main#saas-starter"
          >
            <button class="btn btn-outline btn-primary btn-sm px-6 mt-3 mx-2"
              >Read more</button
            >
          </a>
        </div>
      </div>

      <!-- Exchange -->
      <div class="p-4 border border-gray-200 rounded-lg">
        <img
          src="images/logos/exchange-icon.svg"
          alt=""
          class="mb-4 max-w-full h-auto"
        />

        <h3 class="text-lg font-semibold mb-2">
          Exchange Signature Management
        </h3>
        <p class="mb-2">
          Simple one-time setup with no ongoing maintenance for Exchange 2016
          and later.
        </p>
        <p class="mb-2">On-premises solution for Exchange.</p>
        <p class="mb-4">Smooth migration path to Office 365.</p>
        <p class="mb-4">
          Complete signature management control for IT Administrators.
        </p>
        <div class="mt-6">
          <a href="/pricing">
            <button class="btn btn-primary btn-sm px-6">Get Started</button>
          </a>
          <a
            href="https://github.com/CriticalMoments/CMSaasStarter/tree/main#saas-starter"
          >
            <button class="btn btn-outline btn-primary btn-sm px-6 mt-3 mx-2"
              >Read more</button
            >
          </a>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="hero min-h-[60vh] mt-12">
  <div class="hero-content text-center pb-16 pt-4 px-4">
    <div class="max-w-lg">
      <div
        class="text-3xl md:text-5xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-primary to-accent mt-4"
      >
        Explore Templates
      </div>
      <div
        class="flex flex-col lg:flex-row mt-8 gap-6 place-content-center content-center"
      >
        <div class="hidden md:block">
          <a href="https://criticalmoments.io" target="_blank" class="link">
            <div class="mockup-browser border">
              <div class="mockup-browser-toolbar">
                <div class="input" style="background:#eee;">
                  https://criticalmoments.io
                </div>
              </div>
              <div class="flex justify-center">
                <img
                  alt="Screenshot of criticalmoments.io homepage"
                  class="aspect-[2044/1242]"
                  src="/images/example-home.png"
                />
              </div>
            </div>
          </a>
        </div>
        <div class="md:hidden">
          <a href="https://criticalmoments.io" target="_blank" class="link">
            <div class="card shadow-xl border overflow-hidden">
              <img
                alt="Screenshot of criticalmoments.io homepage"
                class="aspect-[2044/1242]"
                src="/images/example-home.png"
              />
            </div></a
          >
        </div>
        <div class="min-w-[270px] lg:min-w-[420px] flex mt-6 lg:mt-0">
          <div class="my-auto">
            <div class="px-4 text-lg md:text-xl">
              <a href="https://criticalmoments.io" class="" target="_blank"
                >SaaS Starter was created by <span
                  class="font-bold whitespace-nowrap">Critical Moments</span
                >: a SDK to to help mobile apps
                <span class="underline decoration-secondary decoration-[3px]"
                  >increase conversion rates and app-ratings.</span
                ></a
              >
            </div>
            <div class="px-4 mt-6 text-lg md:text-xl">
              Our <a
                href="https://criticalmoments.io"
                class="link font-bold"
                target="_blank">webpage</a
              > is the best example of SaaS Starter with style and real content.
            </div>
            <div class="mt-4 text-large">
              <a href="https://criticalmoments.io" target="_blank">
                <button class="btn btn-primary btn-wide mt-3"
                  >See it in Action</button
                >
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
