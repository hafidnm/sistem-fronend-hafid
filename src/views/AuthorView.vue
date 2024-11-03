<script setup>
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <main class="flex overflow-hidden flex-col items-center bg-x-lightgrey">
      <section class="flex flex-col mt-32 max-md:mt-10">
        <div class="flex flex-row max-md:max-w-full items-start gap-4">
          <img
            class="w-[251px] h-[294px] mx-48"
            src="@/assets/images/misc/kacamata.jpg"
            alt="Two woman in erase board"
          />
        </div>
        <div class="flex flex-col gap-4">
          <h1
            class="text-x-black text-5xl font-bold leading-[64px] tracking-[-2px]"
          >
            Hey there, I'm Andrew Jonhson
            <hr />
            and welcome to my blog
          </h1>
          <h2 class="text-x-mediumgrey w-[515px] text-[16px] text-start mt-2">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor
            <hr />
            incididunt ut labore et dolore magna aliqua. Non blandit massa enim
            nec. Scelerisque viverra mauris in aliquam sem. At risus viverra
            adipiscing at in tellus.
          </h2>
        </div>
      </section>
    </main>
  </MainLayout>
</template>
