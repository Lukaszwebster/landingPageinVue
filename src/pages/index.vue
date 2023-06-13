<script setup lang="ts">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <main class="">
    <section class="relative mt-40 bg-slate-200 pb-20 sm:pb-28">
      <TheInput />
      <div class="ml-8 mr-8 flex flex-col items-center pt-20">
        <div
          id="result"
          class="items-left mb-20 mt-4 w-full flex flex-col justify-center rounded-lg bg-white sm:max-w-2xl sm:flex-row sm:items-center sm:justify-between"
        />
        <h2 class="text-veryDarkBlue text-center text-2xl font-bold">
          Advanced Statistics
        </h2>
        <p class="text-grayishViolet mt-4 text-center sm:ml-52 sm:mr-52">
          Track how your links are performing across the web with our advanced
          statistics dashboard.
        </p>
      </div>
      <div
        class="relative md:ml-20 md:mr-20 sm:ml-14 sm:mr-14 sm:flex sm:justify-between sm:gap-4"
      >
        <div
          class="absolute left-0 right-0 ml-auto mr-auto h-full w-2 bg-cyan sm:top-48 sm:h-2 sm:w-full"
        />
        <div
          class="relative ml-8 mr-8 mt-20 rounded-md bg-white pb-8 pl-10 pr-10 pt-12 sm:ml-0 sm:mr-0 md:max-w-lg sm:max-w-xs sm:pl-4 sm:pr-4"
        >
          <picture>
            <img
              class="bg-darkViolet absolute left-0 right-0 ml-auto mr-auto overflow-visible rounded-full p-4 -top-8 sm:left-10 sm:ml-0 sm:mr-0"
              src="public/icon-brand-recognition.svg"
              alt=""
            ></picture>
          <h2 class="text-veryDarkBlue text-center text-lg font-bold sm:text-left">
            Brand Recognition
          </h2>
          <p class="text-grayishViolet mt-4 text-center text-sm sm:text-left">
            Boost your brand recognition with each click. Generic links don’t mean a
            thing. Branded links help instil confidence in your content.
          </p>
        </div>

        <div
          class="relative ml-8 mr-8 mt-20 rounded-md bg-white pb-8 pl-10 pr-10 pt-12 sm:top-10 sm:ml-0 sm:mr-0 md:max-w-lg sm:max-w-xs sm:pl-4 sm:pr-4"
        >
          <picture><img
            class="bg-darkViolet absolute left-0 right-0 ml-auto mr-auto overflow-visible rounded-full p-4 -top-8 sm:left-10 sm:ml-0 sm:mr-0"
            src="public/icon-detailed-records.svg"
            alt=""
          ></picture>
          <h2 class="text-veryDarkBlue text-center text-lg font-bold sm:text-left">
            Detailed Records
          </h2>
          <p class="text-grayishViolet mt-4 text-center text-sm sm:text-left">
            Gain insights into who is clicking your links. Knowing when and where
            people engage with your content helps inform better decisions.
          </p>
        </div>
        <div
          class="relative ml-8 mr-8 mt-20 rounded-md bg-white pb-8 pl-10 pr-10 pt-12 sm:top-20 sm:ml-0 sm:mr-0 md:max-w-lg sm:max-w-xs sm:pl-4 sm:pr-4"
        >
          <picture><img
            class="bg-darkViolet absolute left-0 right-0 ml-auto mr-auto overflow-visible rounded-full p-3 -top-9 sm:left-10 sm:ml-0 sm:mr-0"
            src="public/icon-fully-customizable.svg"
            alt=""
          ></picture>
          <h2 class="text-veryDarkBlue text-center text-lg font-bold sm:text-left">
            Fully Customizable
          </h2>
          <p class="text-grayishViolet mt-4 text-center text-sm sm:text-left">
            Improve brand awareness and content discoverability through customizable
            links, supercharging audience engagement.
          </p>
        </div>
      </div>
    </section>
    <section
      class="bg-darkViolet bg-boostMobile sm:bg-boostDesktop bg-cover bg-no-repeat pb-20 pt-20"
    >
      <h2 class="text-center text-2xl font-bold text-white">
        Boost your links today
      </h2>
      <div class="flex justify-center">
        <button
          class="mt-4 rounded-3xl bg-cyan pb-2 pl-8 pr-8 pt-2 font-bold text-white hover:bg-teal-200"
        >
          Get Started
        </button>
      </div>
    </section>
  </main>
</template>

<route lang="yaml">
meta:
  layout: default
</route>
