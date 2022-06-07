<template>
  <div class="home">
    <Navbar />
    <Working />
    <Best />
    <Vendoo />
    <May />
    <Pixel />
    <Ceo />
    <Cola />
    <Work />
    <Java />
    <Online />
    <Finish />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Working from "@/components/Working.vue";
import Best from "@/components/Best.vue";
import Vendoo from "@/components/Vendoo.vue";
import May from "@/components/May.vue";
import Pixel from "@/components/Pixel.vue";
import Ceo from "@/components/Ceo.vue";
import Cola from "@/components/Cola.vue";
import Work from "@/components/Work.vue";
import Java from "@/components/Java.vue";
import Online from "@/components/Online.vue";
import Finish from "@/components/Finish.vue";
export default {
  name: "Home",
  components: {
    Navbar,
    Working,
    Best,
    Vendoo,
    May,
    Pixel,
    Ceo,
    Cola,
    Work,
    Java,
    Online,
    Finish,
  },
};
</script>
<style lang="scss" scoped>
.home {
  position: relative;
}
</style>
