<script setup>

</script>

<template>
  <div class="input" style="display: block;">
    <div class="input-1">
      <div class="input-2">
        <div class="option">
          <span role="img" class="anticon">
            <svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class="">
              <use xlink:href="#extend-upload-line"></use>
            </svg>
          </span>
        </div>
        <div class="chat">
          <div class="chat-1">
            <textarea placeholder="登录后免费使用通义" maxlength="10000" class="chat-2" style="overflow-y: hidden; resize: none; height: 24px; min-height: 24px; max-height: 96px;"></textarea>
          </div>
        </div>
        <div class="disable">
          <span role="img" class="anticon">
            <svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class="">
              <use xlink:href="#icon-fasong_default"></use>
            </svg>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.input{
  box-sizing: content-box;
  margin-top: 18px;
  max-width: 896px;
  min-width: 120px;
  position: relative;
  transition: all .2s;
  width: calc(100% - 48px) !important;
  z-index: 999;
}
.input-1{
  align-items: center;
  background: #fff;
  border: 1px solid #615ced;
  border-radius: 20px;
  box-shadow: 0 12px 24px -16px rgba(54, 54, 73, .04), 0 12px 40px 0 rgba(51, 51, 71, .08), 0 0 1px 0 rgba(44, 44, 54, .02);
  box-sizing: content-box;
  display: flex;
  flex-direction: column;
  position: relative;
  transition: border .4s ease;
  width: 100%;
}
.input-2{
  align-items: flex-end;
  display: flex;
  flex: 1;
  margin: 0 auto;
  overflow: auto;
  padding: 6px 8px 6px 16px;
  position: relative;
  width: 100%;
  z-index: 2;
}
.option{
  align-items: center;
  background: #fff;
  cursor: pointer;
  display: flex;
  height: 43px;
  justify-content: center;
  margin-right: 14px;
}
.anticon{
  font-size: 24px !important;
  display: inline-flex;
  align-items: center;
  color: #fff;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -0.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
}
.chat{
  flex: 1;
  height: 100%;
  position: relative;
}
.chat-1{
  height: 100%;
  margin-bottom: 10px;
  overflow: auto;
}
.chat-2{
  transform: translateY(0px);
  opacity: 1;
  background: transparent !important;
  border: 0;
  box-shadow: none !important;
  caret-color: #26244c !important;
  color: #26244c !important;
  font-size: 16px;
  line-height: 24px;
  margin-top: 6px;
  outline: 0;
  padding: 0 8px 0 0;
  transition: none !important;
  width: 100%;
  text-overflow: ellipsis;
  vertical-align: bottom;
  animation: fade-in--qNBrAyIf .15s ease-in-out forwards;
  box-sizing: border-box;
  list-style: none;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  position: relative;
}
.disable{
  background: #d6d5de;
  color: #fff;
  align-items: center;
  border-radius: 20px;
  cursor: pointer;
  display: flex;
  flex-shrink: 0;
  height: 40px;
  justify-content: center;
  margin-left: 16px;
  position: relative;
  width: 40px;
}
</style>