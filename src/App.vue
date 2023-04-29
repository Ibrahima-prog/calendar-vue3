<template>
  <div id="app">
    <AppHeader />
  <div class="w-full flex">
    <!-- <DcHeros /> -->
    <!-- <DcHeros /> -->
    <MyCalendar />
  </div>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader";
// import DcHeros from "./components/DcHeros";
import MyCalendar from "./components/MyCalendar";
// import DcHeros from "./components/DcHeros";
export default {
  // components: { AppHeader, DcHeros },
  components: { AppHeader, MyCalendar },
};
</script>

<style>

</style>
