<template>
  <div class="docker">
    <div class="docker__item docker__item--active">
      <div class="iconfont">&#xe661;</div>
      <div class="docker__item__title">首页</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe6bc;</div>
      <div class="docker__item__title">购物车</div>
    </div>

    <div class="docker__item">
      <div class="iconfont">&#xe64b;</div>
      <div class="docker__item__title">订单</div>
    </div>
    <div class="docker__item">
      <div class="iconfont">&#xe78b;</div>
      <div class="docker__item__title">我的</div>
    </div>
  </div>
</template>

<script>
export default {
  name: '',
  components: {},
  props: {}
}
</script>
<style lang="scss" scoped>
@import '../../style/viriables.scss';
@import '../../style/mixins.scss';
.wrapper {
}
.docker {
  display: flex;
  box-sizing: border-box;
  position: absolute;
  padding: 0 0.18rem;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 0.49rem;
  border-top: 1px solid $content-bgcolor;
  color: #333;
  &__item {
    flex: 1;
    text-align: center;
    &__title {
      font-size: 16px;
      transform: scale(0.5 0.5);
      transform-origin: center top;
    }
    &--active {
      color: #1fa4fc;
    }
  }
}
</style>
