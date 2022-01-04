<template>
  <!-- Mobile menu button-->
  <DisclosureButton
    type="button"
    class="bg-gray-800 p-1 rounded-full text-gray-400 hover:text-white focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white"
  >
    <span class="sr-only">View notifications</span>
    <BellIcon class="h-6 w-6" aria-hidden="true" />
  </DisclosureButton>
</template>

<script setup lang="ts">
import {
  Disclosure,
  DisclosureButton,
  DisclosurePanel,
  Menu,
  MenuButton,
  MenuItem,
  MenuItems,
} from "@headlessui/vue";
import { BellIcon, MenuIcon, XIcon } from "@heroicons/vue/outline";
</script>

<style></style>
