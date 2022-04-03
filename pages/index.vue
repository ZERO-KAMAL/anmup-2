<template>
  <div>
    <MainBanner></MainBanner>
    <Mission></Mission>
    <Services></Services>
    <Introduction></Introduction>
    <Work></Work>
    <Feedback></Feedback>
  </div>
</template>

<script>
import Mission from "../Landing/Mission.vue";
import MainBanner from "../Landing/MainBanner.vue";
import Feedback from "../Landing/Feedback.vue";
import Services from "../Landing/Services.vue";
import Introduction from "~/Landing/Introduction.vue";
import Work from "~/Landing/Work.vue";
export default {
  name: "IndexPage",
  components: {
    MainBanner,
    Mission,
    Services,
    Feedback,
    Introduction,
    Work,
  },
};
</script>
