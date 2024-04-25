<script setup lang="ts">
import { Page } from "ui";
import { name } from "../package.json";
</script>

<template>
  <Page :app-name="name" />
  <div class="bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500  h-96">123</div>
</template>
