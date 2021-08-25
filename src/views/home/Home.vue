<template>
  <div>
    <div class="wrapper">
      <staicpart></staicpart>
      <nearby></nearby>
    </div>
    <docker />
  </div>
</template>

<script>
import StaicPart from './StaticPart.vue'
import Nearby from './Nearyby.vue'
import Docker from './Docker.vue'
export default {
  name: 'Home',
  components: {
    staicpart: StaicPart,
    nearby: Nearby,
    docker: Docker
  }
}
</script>

<style lang="scss">
@import '../../style/viriables.scss';
@import '../../style/mixins.scss';
.wrapper {
  overflow-y: auto;
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0.5rem;
  right: 0;
  padding: 0 0.18rem;
}
</style>
