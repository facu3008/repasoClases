<script setup>
// import HelloWorld from "./components/HelloWorld.vue";
// import MyFirstComponent from "./components/vueBasics/0-MyFirstComponent.vue";
// import TextDirective from "./components/vueBasics/2-TextDirective.vue";
// import HtmlDirective from "./components/vueBasics/3-HtmlDirective.vue";
// import AttributeBinding from "./components/vueBasics/4-attribute-binding.vue";
import ConditionalRendering from "./components/vueBasics/5-ConditionalRendering.vue";
// import IteratingElements from "./components/vueBasics/7-IteratingElements.vue";
// import Methods from "./components/vueBasics/7-Methods.vue";
// import ComputedProperties from "./components/vueBasics/8-ComputedProperties.vue";
// import TwoWayDataBinding from "./components/vueBasics/9-TwoWayData.vue";
//import Watchers from "./components/vueBasics/10-Watchers.vue";
// import Events from "./components/vueBasics/11-Events.vue";
// import Hooks from "./components/vueBasics/12-Hooks.vue";
</script>

<template>
  <div>

    <header>
      <div class="wrapper">
        <HelloWorld msg="Hooks" />
      </div>
    </header>
    <main>
      <!-- <MyFirstComponent /> -->
      <!-- <TextDirective /> -->
      <!-- <HtmlDirective /> -->
      <!-- <AttributeBinding /> -->
      <ConditionalRendering />
      <!-- <IteratingElements /> -->
      <!-- <Methods /> -->
      <!-- <ComputedProperties /> -->
      <!-- <TwoWayDataBinding /> -->
      <!-- <Watchers /> -->
      <!-- <Events /> -->
      <!-- <Hooks /> -->
    </main>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
