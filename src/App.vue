<template>
  <div id="app" class="font-sans text-black antialiased border-t-2 border-indigo">
    <site-header />
    <div class="container mx-auto flex items-center mt-4 px-6 md:px-3">
      <div class="max-w-lg w-full">
        <h1 class="text-3xl md:text-4xl font-normal leading-normal">We craft beautiful and powerful fullstack web and android applications.</h1>
        <div class="mt-8">
          <a href="#" class="uppercase tracking-wide text-sm no-underline inline-block bg-black rounded px-6 py-3 text-white">Start a project</a>
        </div>
      </div>
      <div class="w-full p-4 hidden md:block">
        <img src="./assets/app-user-monochrome.svg" alt="We craft beautiful and powerful fullstack web and android applications.">
      </div>
    </div>
    <div class="container mx-auto mt-10 px-6 md:px-3">
      <div class="block md:flex leading-normal items-center">
        <div class="flex-1 md:pr-6 mb-8">
          <h1 class="font-normal text-3xl mb-2">How we work</h1>
          <p class="text-base">Think of us as 'wizards'.</p>
          <p class="text-base">Whether your project is big or small, we can jump in,<br> do our thing and make seriously cool stuff happen.</p>
          <p><a href="#" class="no-underline text-black mt-3 inline-block border-b border-black">Learn a bit more about us →</a></p>
        </div>
        <div class="flex-1 md:pl-6">
          <div class="mb-8">
            <h2 class="font-normal text-2xl mb-2">We ask questions</h2>
            <p class="text-base">We're not a "build me a website" type of agency. We ask the right questions to make sure we understand you and your brand in order to build a successful project.</p>
          </div>
          <div class="mb-4">
            <h2 class="font-normal text-2xl mb-2">We design <i>and/or</i> build</h2>
            <p class="text-base">We can come up with wireframes, website design and interactive prototypes. Already got designs? No problem! We love to build.</p>
          </div>
        </div>
      </div>
    </div>
    <site-footer />
  </div>
</template>

<script>
import './assets/main.css'

import SiteHeader from './components/SiteHeader'
import SiteFooter from './components/SiteFooter'

export default {
  name: 'app',
  components: {
    SiteHeader,
    SiteFooter,
  }
}
</script>