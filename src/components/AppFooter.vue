<template lang="pug">
footer
  .container
      ul.navbar-list
        li.navbar-item(v-for="link in links" :key="link.alias")
          router-link.navbar-link(:to="link.url") {{ link.title }}
</template>

<script>
/* eslint-disable quotes */
import { links } from "@/_config";

export default {
  data() {
    return {
      links,
    };
  },
};
</script>
