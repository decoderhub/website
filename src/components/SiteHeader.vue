<template>
    <div class="py-6">
      <div class="container mx-auto flex items-center justify-between px-6 md:px-3">
        <div class="flex-1 flex items-center">
          <span class="inline-block bg-white rounded-tl-lg rounded-br-lg text-black flex items-center justify-center">
            <svg class="fill-current w-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 44.25 38.92"><g><path class="cls-1" d="M14.64,17.89,34.44,0h-27L0,38.92H30.64A9.69,9.69,0,0,0,32,38.83L14.54,21.1A2.22,2.22,0,0,1,14.64,17.89Z"/><path class="cls-1" d="M38.74,4.16l-16,14.43a1.91,1.91,0,0,0-.08,2.76L35.76,34.67a8.59,8.59,0,0,0,3.57-5.48l3.1-16.25A8.59,8.59,0,0,0,38.74,4.16Z"/></g></svg>
          </span>
          <span class="ml-2 hidden md:inline">/ decoderhub</span>
        </div>
        <div class="hidden md:block text-center flex-1">
          <a href="#" class="mx-3 no-underline text-black">Home</a>
          <a href="#" class="mx-3 no-underline text-black">About</a>
          <a href="#" class="mx-3 no-underline text-black">Contact</a>
        </div>
        <div class="flex-1 text-right hidden md:block">
          <a href="#" class="uppercase tracking-wide text-xs no-underline inline-block bg-indigo rounded px-4 py-3 text-white">Start a project</a>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'SiteHeader',
}
</script>
