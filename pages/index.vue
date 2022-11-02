<template>
  <div>
    <div>
      <nuxt-img
        placeholder
        format="webp"
        sizes="sm:100vw md:50vw lg:800px"
        src="/ivan-torres-MQUqbmszGGM-unsplash.jpg"
        alt=""
      />
    </div>
    <div>
      <a class="info" href="https://image.nuxtjs.org/" target="_blank">
        @nuxt/image homepage & docs
      </a>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default {
  data: () => ({
    message: "Hello World!",
  }),
};
</script>