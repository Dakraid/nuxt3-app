<template>
  <div class="container max-w-screen-xl mx-auto py-6">
    <NavBar />
  </div>
  <div class="container max-w-screen-xl mx-auto py-6">
    <Hero />
  </div>
  <div class="max-w mx-auto">
    <div class="flex justify-center items-center gap-6 my-6">
    </div>
  </div>
</template>

<script lang="ts">
import { NuxtLink } from "#components";
import { ExternalLinkIcon } from "@heroicons/vue/outline";
export default {
  components: {
    NuxtLink,
    ExternalLinkIcon,
  }
};
</script>
