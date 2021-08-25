<template>
  <div class="nearby">
    <div class="nearby__title">附近店铺</div>
    <div class="nearby__item">
      <img src="http://www.dell-lee.com/imgs/vue3/near.png" alt="" class="nearby__item__img" />
      <div class="nearby__content">
        <div class="nearby__content__title">沃尔玛</div>
        <div class="nearby__content__tags">
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
        </div>
        <p class="nearby__content__highlight">VIP尊享满89元减4元运费券（每月3张)</p>
      </div>
    </div>
    <div class="nearby__item">
      <img src="http://www.dell-lee.com/imgs/vue3/near.png" alt="" class="nearby__item__img" />
      <div class="nearby__content">
        <div class="nearby__content__title">沃尔玛</div>
        <div class="nearby__content__tags">
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
        </div>
        <p class="nearby__content__highlight">VIP尊享满89元减4元运费券（每月3张)</p>
      </div>
    </div>
    <div class="nearby__item">
      <img src="http://www.dell-lee.com/imgs/vue3/near.png" alt="" class="nearby__item__img" />
      <div class="nearby__content">
        <div class="nearby__content__title">沃尔玛</div>
        <div class="nearby__content__tags">
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
        </div>
        <p class="nearby__content__highlight">VIP尊享满89元减4元运费券（每月3张)</p>
      </div>
    </div>
    <div class="nearby__item">
      <img src="http://www.dell-lee.com/imgs/vue3/near.png" alt="" class="nearby__item__img" />
      <div class="nearby__content">
        <div class="nearby__content__title">沃尔玛</div>
        <div class="nearby__content__tags">
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
          <span class="nearby__content__tag">月销1万+</span>
        </div>
        <p class="nearby__content__highlight">VIP尊享满89元减4元运费券（每月3张)</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Nearby',
  components: {},
  props: {}
}
</script>
<style lang="scss">
@import '../../style/viriables.scss';
@import '../../style/mixins.scss';
.nearby {
  &__title {
    margin: 0.16rem 0 0.04rem 0;
    font-size: 0.18rem;
    font-weight: normal;
    color: $content-fontcolor;
  }
  &__item {
    display: flex;
    padding: 0.12rem;
    &__img {
      margin-right: 0.16rem;
      width: 0.56rem;
      height: 0.56rem;
    }
  }
  &__content {
    flex: 1;
    border-bottom: 1px solid $content-bgcolor;
    &__title {
      font-size: 0.06rem;
      line-height: 0.22rem;
    }
    &__tags {
      line-height: 0.18rem;
      font-size: 0.13rem;
      color: $content-fontcolor;
    }
    &__tag {
      margin-right: 0.16rem;
    }
    &__highlight {
      margin: 0.08rem 0;
      line-height: 0.18rem;
      font-size: 0.13rem;
      color: #e93b3b;
    }
  }
}
</style>
