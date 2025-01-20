<template>

  <Head>
    <title>My App</title>
    <meta head-key="description" name="description" content="My App default description." />
  </Head>
  <div class="">
    <header class="bg-indigo-500 text-white">
      <nav class="flex items-center jusbrify-between p-4 max-w-screen-lg mx-auto">
        <div class=" space-x-6">
          <Link :href="route('home')">Home</Link>
          <Link :href="route('about')">About</Link>
        </div>
      </nav>
    </header>

    <main class="p-4">
      <slot />
    </main>
  </div>
</template>

<script setup>
import { route } from '../../../vendor/tightenco/ziggy/src/js';

</script>

<style lang="css" scoped></style>
