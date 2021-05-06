# mnxm-live2d-vue
在vue中使用live2d

## 安装
npm install mnxm-live2d-vue

## 使用
main.js
```
import Vue from 'vue'
import Live2d from 'mnxm-live2d-vue'
Vue.component('Live2d', Live2d);
```
page.vue
```
<Live2d ref="main" class="main" :modelData="mdata" :on-move="handleMove" :width="300" :height="300" />
```

## 示例
