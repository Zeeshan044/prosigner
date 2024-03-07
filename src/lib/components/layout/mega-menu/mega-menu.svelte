<script lang="ts">
  export let menu: any
</script>

<!-- Menu -->
<div
  class="bg-[#f8f9fb] absolute top-full left-0 right-0 border-t border-[#f8f9fb]"
>
  <div class="container mx-auto grid grid-cols-4 gap-8 px-8">
    <div class="py-8">
      <h3 class="uppercase font-bold text-sm">Our Products</h3>
      <div class="flex flex-col mt-4 gap-4">
        <!-- Card -->
        <div
          class="border border-gray-300 group hover:border-secondary hover:shadow rounded-lg py-4 px-5 bg-white flex flex-col gap-4 duration-100"
        >
          <div class="flex items-center gap-2">
            <span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="28"
                height="28"
                viewBox="0 0 28 28"
                fill="none"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M24.4006 5.5H3.59936C2.9922 5.5 2.5 5.9922 2.5 6.59936V22.3684C2.5 22.9755 2.9922 23.4677 3.59936 23.4677H24.4006C25.0078 23.4677 25.5 22.9755 25.5 22.3684V6.59936C25.5 5.9922 25.0078 5.5 24.4006 5.5ZM3.59936 4C2.16377 4 1 5.16378 1 6.59936V22.3684C1 23.804 2.16377 24.9677 3.59936 24.9677H24.4006C25.8362 24.9677 27 23.804 27 22.3684V6.59936C27 5.16377 25.8362 4 24.4006 4H3.59936ZM7.76071 10.5747V13.7342H10.9202V10.5747L7.76071 10.5747ZM7.0107 9.07472L11.6702 9.0747C11.8691 9.0747 12.0599 9.15372 12.2005 9.29437C12.3412 9.43502 12.4202 9.62579 12.4202 9.8247V14.4842C12.4202 14.8984 12.0844 15.2342 11.6702 15.2342H7.01071C6.59649 15.2342 6.26071 14.8984 6.26071 14.4842V9.82472C6.26071 9.4105 6.59649 9.07472 7.0107 9.07472ZM16.3299 9.0747C15.9157 9.0747 15.5799 9.41049 15.5799 9.8247C15.5799 10.2389 15.9157 10.5747 16.3299 10.5747H20.9894C21.4036 10.5747 21.7394 10.2389 21.7394 9.8247C21.7394 9.41049 21.4036 9.0747 20.9894 9.0747H16.3299ZM15.5799 14.4841C15.5799 14.0698 15.9157 13.7341 16.3299 13.7341H20.9894C21.4036 13.7341 21.7394 14.0698 21.7394 14.4841C21.7394 14.8983 21.4036 15.2341 20.9894 15.2341H16.3299C15.9157 15.2341 15.5799 14.8983 15.5799 14.4841ZM7.01071 18.3939C6.59649 18.3939 6.26071 18.7297 6.26071 19.1439C6.26071 19.5581 6.59649 19.8939 7.01071 19.8939H20.9892C21.4034 19.8939 21.7392 19.5581 21.7392 19.1439C21.7392 18.7297 21.4034 18.3939 20.9892 18.3939H7.01071Z"
                  fill="currentColor"
                ></path></svg
              >
            </span>
            <span class="font-bold">Email signature generator</span>
          </div>
          <p>
            Create a stunning email signature for yourself within a few clicks
          </p>
          <div class="flex">
            <div
              class="text-xs border px-1 border-primary bg-[#f8f9fb] group-hover:border-secondary group-hover:text-secondary"
            >
              For individual
            </div>
          </div>
        </div>
        <!-- Card -->
        <div
          class="border border-gray-300 group hover:border-secondary hover:shadow-lg rounded-lg py-4 px-5 bg-white flex flex-col gap-4 duration-100"
        >
          <div class="flex items-center gap-2">
            <span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="28"
                height="28"
                viewBox="0 0 28 28"
                fill="none"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M24.4006 5.5H3.59936C2.9922 5.5 2.5 5.9922 2.5 6.59936V22.3684C2.5 22.9755 2.9922 23.4677 3.59936 23.4677H24.4006C25.0078 23.4677 25.5 22.9755 25.5 22.3684V6.59936C25.5 5.9922 25.0078 5.5 24.4006 5.5ZM3.59936 4C2.16377 4 1 5.16378 1 6.59936V22.3684C1 23.804 2.16377 24.9677 3.59936 24.9677H24.4006C25.8362 24.9677 27 23.804 27 22.3684V6.59936C27 5.16377 25.8362 4 24.4006 4H3.59936ZM7.76071 10.5747V13.7342H10.9202V10.5747L7.76071 10.5747ZM7.0107 9.07472L11.6702 9.0747C11.8691 9.0747 12.0599 9.15372 12.2005 9.29437C12.3412 9.43502 12.4202 9.62579 12.4202 9.8247V14.4842C12.4202 14.8984 12.0844 15.2342 11.6702 15.2342H7.01071C6.59649 15.2342 6.26071 14.8984 6.26071 14.4842V9.82472C6.26071 9.4105 6.59649 9.07472 7.0107 9.07472ZM16.3299 9.0747C15.9157 9.0747 15.5799 9.41049 15.5799 9.8247C15.5799 10.2389 15.9157 10.5747 16.3299 10.5747H20.9894C21.4036 10.5747 21.7394 10.2389 21.7394 9.8247C21.7394 9.41049 21.4036 9.0747 20.9894 9.0747H16.3299ZM15.5799 14.4841C15.5799 14.0698 15.9157 13.7341 16.3299 13.7341H20.9894C21.4036 13.7341 21.7394 14.0698 21.7394 14.4841C21.7394 14.8983 21.4036 15.2341 20.9894 15.2341H16.3299C15.9157 15.2341 15.5799 14.8983 15.5799 14.4841ZM7.01071 18.3939C6.59649 18.3939 6.26071 18.7297 6.26071 19.1439C6.26071 19.5581 6.59649 19.8939 7.01071 19.8939H20.9892C21.4034 19.8939 21.7392 19.5581 21.7392 19.1439C21.7392 18.7297 21.4034 18.3939 20.9892 18.3939H7.01071Z"
                  fill="currentColor"
                ></path></svg
              >
            </span>
            <span class="font-bold">Email signature manager</span>
          </div>
          <p>
            Manage your team email signature and gain control over your brand.
          </p>
          <div class="flex">
            <div
              class="text-xs border px-1 border-primary bg-[#f8f9fb] group-hover:border-secondary group-hover:text-secondary"
            >
              For organizations
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-white rounded-s-lg col-span-3 flex place-content-center p-8">
      <div class="grid grid-cols-4 gap-8">
        <div class="col-span-3 grid grid-cols-3 gap-8">
          {#each menu as item}
            <div>
              <h3 class="uppercase font-bold text-sm">{item.title}</h3>
              <ul class="flex flex-col gap-3 mt-4">
                {#each item.items as link}
                  <li class="hover:text-secondary duration-100 cursor-pointer">
                    {link}
                  </li>
                {/each}
              </ul>
            </div>
          {/each}
        </div>
        <div>
          <h3 class="uppercase font-bold text-sm">User Stories</h3>
          <img
            src="https://www.wisestamp.com/wp-content/uploads/2023/09/menu-review-img.jpg"
            alt=""
            class="mt-4"
          />
          <p class="text-sm mt-2 ml-2">
            See how companies save time & money automating their email
            signatures
          </p>
        </div>
      </div>
    </div>
  </div>
</div>
