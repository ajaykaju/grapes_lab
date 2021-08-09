<template>
  <div class="home">
    <section class="sec1">
      <nav-bar class="nav"></nav-bar>
      <div class="background">
        <div class="b1"></div>
        <div class="b2"></div>
      </div>
      <div class="content">
        <div class="content1">
          <div class="title">Gym Gives You The Perfect Health</div>
          <div class="description">
            It is a long established fact that a reader will be by readable
            content of a page when are best product
          </div>
          <div class="actions">
            <div class="shop_button">Shop now</div>
            <div class="watch_videos"><div class="icon"><img src="../assets/icons/play.svg"></div> Watch videos</div>
          </div>
        </div>
        <div class="content2">
          <img src="../assets/dumbbell.png">
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import NavBar from "@/components/NavBar.vue";
import { defineComponent } from "vue";

export default defineComponent({
  components: { NavBar },
  //   setup() {

  //   },
});
</script>



<style lang="sass" scoped>
@import "../styles/home"
</style>