<template>
  <div id="app">
    <h2 class="title">vue-mobile-calendar</h2>
    <demo1 />
    <demo2 />
    <demo3 />
    <demo4 />
  </div>
</template>

<script>
import demo1 from './demos/demo1.vue';
import demo2 from './demos/demo2.vue';
import demo3 from './demos/demo3.vue';
import demo4 from './demos/demo4.vue';
export default {
  components: {
    demo1,
    demo2,
    demo3,
    demo4,
  },
};
</script>

<style lang="less">
html,
body {
  margin: 0;
  padding: 0;
  background: #eee;
}
#app{
  padding: 0 10px;
}
.btn{
  padding: 5px 10px;
}
.title{
  text-align: center;
}
.demo{
  border-radius: 2px;
  box-shadow: 0 1px 5px rgba(0,0,0,.2), 0 2px 2px rgba(0,0,0,.14), 0 3px 1px -2px rgba(0,0,0,.12);
  margin-bottom: 20px;
}
.demo-title{
  padding: 10px 0;
  font-size: 16px;
  border-bottom: 1px solid #eee;
  margin-bottom: 20px;
}
</style>
