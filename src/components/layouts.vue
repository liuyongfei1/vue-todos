<template>
  <section class="container"> <!--最外层容器-->
    <section class="menu"> <!--左边的容器-->
      <menus></menus>
    </section>
    <section class="content-container"><!--右边的容器-->
    </section>
  </section>
</template>
<script>
import menus from './menus'
export default {
  components: { // * 注册menus组件，让其可以在template调用
    menus
  }
}
</script>
<style lang="less">
  @import '../common/style/layouts.less';
</style>
