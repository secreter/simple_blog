<template>
  <div id="app">
    <hello></hello>
    <!-- 路由出口 -->
    <!-- 路由匹配到的组件将渲染在这里 -->
    <transition name="fade">
      <router-view></router-view>
    </transition>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
body{
  background-color: var(--primary-bg-color);
}

</style>
