<script>
import Aside from './components/Aside.vue'
import ExpandablePanel from "@/components/ExpandablePanel.vue";
import Main from "@/components/Main.vue";
export default {
  components: {
    Aside,
    ExpandablePanel,
    Main,
  }
}
</script>

<template>
<div id="ice-container" style="filter:blur(0px)">
  <div class="layout--BjBO2Tgb">
    <div class="body-1">
      <div class="body">
      <Aside></Aside>
        <div>
      <ExpandablePanel></ExpandablePanel>
          <Main></Main>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<style scoped>
.layout--BjBO2Tgb {
  align-items: stretch;
  display: flex;
  flex-direction: row;
  height: 100%;
  position: relative;
  width: 100%;
}

</style>

