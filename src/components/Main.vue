<script >
import Between from "@/components/Between.vue";
import Input from "@/components/Input.vue";
import Root from "@/components/Root.vue";
export default {
  components: {
    Between,
    Input,
    Root
  }
}
</script>

<template>
<div class="main-1">
  <div class="main-2 addition-1">
<div class="head">
  <div class="head-1">
    <div class="head-2">
      <span role="img" class="anticon icon--OFMlpLso">
        <svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class="">
          <use xlink:href="#tongyi-jia-plus-line"></use>
        </svg>
      </span>
    </div>
    <div  style="color: #2c2c36;font-size: 16px;margin-left: 12px;">Qwen </div>
  </div>
<div class="top">
  <div></div>
</div>
</div>
<!--    <div class="body-1" style="display: block">-->
<!--      <div class="content">-->
<!--        <div class="content-1"></div>-->
<!--      </div>-->
<!--    </div>-->
    <div class="down"></div>
    <div></div>
    <Between></Between>
    <Input></Input>
    <Root></Root>
    <div></div>
  </div>
  <div class="xing"></div>
</div>
</template>

<style scoped>
.main-1{
  flex: 1 1 0;
  height: 100%;
  overflow-x: auto;
  width: 1600px;
}
.main-2{
  align-items: center;
  animation: fadeInBackground--H8JcMAHC .4s ease forwards;
  background-color: #f6f7fb;
  display: flex;
  flex: 1;
  flex-direction: column;
  height: 95%;
  min-width: 95px;
  transition: all .4s ease;
}
.addition-1{
  background: linear-gradient(180deg, #fff 64%, #fff 85%);
  box-shadow: 0 0 24px 0 rgba(88, 90, 115, .12);
  position: relative;
  transition: all .4s ease;
}
.head{
  height: 70px;
  position: relative;
  width: 100%;
}
.head-1{
  align-items: center;
  border-radius: 8px;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  height: 36px;
  line-height: 32px;
  margin: 24px 0 8px 24px;
  text-align: center;
  transition: all .4s ease;
  z-index: 5;
}
.head-2{
  background-color: #615ced;
  border-radius: 50%;
  height: 18px;
  width: 18px;
  justify-content: center;
  align-items: center;
  display: flex;
}
.anticon {
  display: inline-flex;
  align-items: center;
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -0.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.icon--OFMlpLso {
  color: #fff;
  height: 16px;
  justify-content: center;
  width: 16px;
}
.top{
  align-items: center;
  display: flex;
  position: absolute;
  right: 26px;
  top: 24px;
}
.body-1{
  align-items: center;
  display: flex;
  flex: 1;
  flex-direction: column;
  overflow-y: auto;
  position: relative;
  transition: all .4s ease;
  width: 100%;
  z-index: 3;
}
.content{
  flex: 1;
  overflow-x: hidden;
  width: 100%;
}
.down{
  height: 0;
  width: 100%;
}
.content-1{
  display: flex;
  flex-direction: column-reverse;
  max-height: calc(100vh - 270px);
  overflow: auto;
}
.xing{

}
</style>