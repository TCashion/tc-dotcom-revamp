<template>
  <div>
    <nuxt-link to="/blog">Blog</nuxt-link>
    <nuxt-link to="/portfolio">Portfolio</nuxt-link>
    <nuxt-link to="/about">About</nuxt-link>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "nuxt-property-decorator";

@Component
export default class NavBar extends Vue {}
</script>

<style></style>
