<template>
  <div id="cesiumContainer"></div>
</template>

<script>
import * as Cesium from 'cesium'
import 'cesium/Source/Widgets/widgets.css'
import { initCesium } from '../common/js/initCesium'
export default {
  mounted() {
    let viewer = initCesium(Cesium)
    viewer._cesiumWidget._creditContainer.style.display = 'none' // 隐藏版权信息
  },
}
</script>

<style>
html,
body,
#cesiumContainer {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
}
</style>