<template>
  <header class="font-poppins">
    <ThePopUpWindowFromHamburgerMenu is-open />
    <nav
      class="ml-4 mr-4 mt-8 flex items-center justify-between md:ml-20 md:mr-20 sm:ml-14 sm:mr-14 sm:justify-between"
    >
      <div class="flex items-center gap-4">
        <picture><img src="public/logo.svg" alt="image of logo Shortly"> </picture>
        <ul class="text-grayishViolet hidden sm:flex sm:gap-2">
          <li class="hover:text-veryDarkBlue cursor-pointer">
            Features
          </li>
          <li class="hover:text-veryDarkBlue cursor-pointer">
            Pricing
          </li>
          <li class="hover:text-veryDarkBlue cursor-pointer">
            Resources
          </li>
        </ul>
      </div>
      <div class="hidden sm:flex">
        <button class="text-grayishViolet">
          Login
        </button>
        <button
          class="ml-2 rounded-3xl bg-cyan pb-2 pl-4 pr-4 pt-2 text-white hover:bg-teal-200"
        >
          Sign Up
        </button>
      </div>
      <button class="hamburger sm:hidden">
        <img class="h-8" src="public/bars-solid.svg" alt="menu hamburger">
      </button>
    </nav>
    <div
      class="overflow-hidden md:ml-20 sm:ml-14 sm:mt-4 sm:flex sm:flex-row-reverse sm:items-center sm:justify-between"
    >
      <picture>
        <img
          class="relative left-24 mt-8 sm:left-14 md:max-w-md"
          src="public/illustration-working.svg"
          alt=""
        >
      </picture>
      <div class="sm:mr-10">
        <h1 class="text-veryDarkBlue mt-12 text-center text-4xl font-bold sm:text-left">
          More than just shorter links
        </h1>
        <p
          class="text-grayishViolet ml-4 mr-4 mt-4 text-center text-lg font-medium sm:ml-0 sm:text-left"
        >
          Build your brand’s recognition and get detailed insights on how your links
          are performing.
        </p>
        <div class="flex justify-center sm:justify-start">
          <button
            class="mt-4 rounded-3xl bg-cyan pb-2 pl-8 pr-8 pt-2 text-white hover:bg-teal-200"
          >
            Get Started
          </button>
        </div>
      </div>
    </div>
  </header>
</template>
