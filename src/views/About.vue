<template>
  <div class="about">
    <h1>This is an about page. Version {{ version }}</h1>
  </div>
</template>

<script>
export default {
  name: "about",
  data: function() {
    return {
      version: process.env.VUE_APP_VERSION
    };
  }
};
</script>
