<template>
  <base-lightbox-photos
    :cells="1"
    :items="images"
  />
</template>

<script>
import BaseLightboxPhotos from "@/components/BaseLightboxPhotos";
export default {
  components: {
    BaseLightboxPhotos,
  },
  data() {
    return {
      images: [
        "https://ucarecdn.com/4ee881d2-4b42-4979-b378-a46f3e185b2f/-/crop/698x524/201,0/-/preview/",
        "https://ucarecdn.com/4ee881d2-4b42-4979-b378-a46f3e185b2f/-/crop/698x524/201,0/-/preview/",
        "https://ucarecdn.com/4ee881d2-4b42-4979-b378-a46f3e185b2f/-/crop/698x524/201,0/-/preview/",
      ],
    };
  },
};
</script>
<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
