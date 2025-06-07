<script setup>

</script>

<template>
<div>
  <div class="expand">
    <div class="expand-1">
      <div class="expand-2">
        <div class="side">
          <button type="button" class="ui-button"></button>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<style scoped>
.expand {
  width: 0;
  position: relative;
  transition: width 0.4s;
}
.expand-1{
  background: rgb(255, 255, 255);
  overflow: hidden;
  width: 260px;
  height: 100%;
  position: absolute;
  right: 0;
  top: 0;
  opacity: 0.5;
  transition: opacity 0.2s;
}
.expand-2{
  border-right: 1px solid rgba(237, 239, 245, .45);
  display: flex;
  flex-direction: column;
  flex-shrink: 0;
  height: 100%;
  justify-content: space-between;
  padding: 24px 0;
  position: relative;
  width: 260px;
  z-index: 10;
  background-color: #c6c4ff ;
  color: #fff ;
  cursor: not-allowed;

}
.ui-button{
  background-color: #c6c4ff !important;
  color: #fff !important;
  cursor: not-allowed !important;
  align-items: center;
  border-radius: 32px;
  display: flex;
  flex-shrink: 0;
  font-size: 14px;
  font-weight: 400;
  height: 36px;
  justify-content: center;
  line-height: 24px;
  margin-right: 8px;
  opacity: 1;
  transition: all .3s;
  width: 168px;
}
</style>