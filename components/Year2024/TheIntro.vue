<template>
  <div class="flex flex-col min-h-screen items-center justify-center bg-[url('/bg1.webp')] bg-center bg-cover">
    <div class="w-full max-w-[800px] p-2 flex flex-col flex-grow justify-center text-center">
      <div class="flex flex-col md:flex-row gap-6 md:gap-2 my-4 justify-center items-center text-[#dddddd] font-bold">
        <a href="https://www.evidencz.com/">
          <img
            class="inline-block w-auto h-4 md:h-8 cursor-pointer" src="/eviden.webp"
            title="Eviden Czech Republic" alt="Eviden logo"
          >
        </a>
        <span class="hidden md:inline">&</span>
        <a href="https://www.gopas.cz/">
          <img
            class="inline-block w-auto h-6 md:h-10 cursor-pointer" src="/gopas.webp"
            title="IT training center GOPAS" alt="Gopas logo"
          >
        </a>
        <span class="hidden md:inline">&</span>
        <a href="https://www.exponet.cz/">
          <img
            class="inline-block w-auto h-5 md:h-8 cursor-pointer" src="/exponet.webp"
            title="Exponet - Your Event Manager" alt="Exponet logo"
          >
        </a>
        <span class="hidden md:inline">&</span>
        <a href="https://www.startupjobs.cz/">
          <img
            class="inline-block w-auto h-6 md:h-12 md:pt-2 cursor-pointer" src="/startupjobs.webp"
            title="StartupJobs.cz" alt="StartupJobs.cz logo"
          >
        </a>
      </div>
      <div class="text-xl text-[#dddddd] mb-6 md:mb-8">
        {{ $t('intro.present') }}
      </div>
      <div>
        <img
          class="inline-block w-auto h-40 cursor-pointer mb-2" src="/pragvue.svg"
          title="PragVue" alt="PragVue logo"
        >
      </div>
      <div class="flex flex-col min-[660px]:flex-row justify-center mb-4">
        <h1 class="inline-block mx-4 text-[56px] md:text-[72px]">
          <span class="font-bold">PragVue</span> 2024
        </h1>
      </div>
      <div class="mb-1 text-2xl text-[#dddddd]">
        {{ $t('intro.about') }}
      </div>
      <div class="mb-10 text-2xl font-bold">
        {{ $t('intro.date') }}
      </div>
      <div class="mb-10 text-xl text-[#dddddd]">
        {{ $t('intro.place') }}
        <a href="https://maps.app.goo.gl/kYzHaNKrc346BVfbA">🗺️</a>
      </div>
      <a href="#idea">
        <button :class="BUTTON_LIGHT">
          {{ $t('intro.more') }}
        </button>
      </a>
    </div>
  </div>
</template>
