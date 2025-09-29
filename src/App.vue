<script setup lang="ts"></script>

<template>
  <h1>You did it!</h1>
  <span is-="badge">badge</span>
</template>

<style>
@layer base, utils, components;

@import '@webtui/css/base.css';


/* Utils */
@import '@webtui/css/utils/box.css';

/* Components */
@import '@webtui/css/components/button.css';
@import '@webtui/css/components/typography.css';
@import '@webtui/css/components/badge.css';

/* Import theme AFTER all other WebTUI CSS */
@import '@webtui/theme-catppuccin';


</style>
