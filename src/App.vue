<template lang="pug">
AppHeader
.wrapper-content
  .container
    router-view
AppFooter
</template>

<script>
/* eslint-disable quotes */
/* eslint-disable import/extensions */
import AppHeader from "@/components/AppHeader";
import AppFooter from "@/components/AppFooter";

export default {
  components: { AppHeader, AppFooter },
};
</script>

<style></style>
