<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import { defineAsyncComponent } from "vue"

const RemoteButton = defineAsyncComponent(() => import('ContactApp/ContactPage'));
</script>

<template>
  <main>
    <p>kkkkkkkkkkk</p>
    <RemoteButton />
    <TheWelcome />
  </main>
</template>
