<template>
  <div>
    <leftbar/>
    <div class="connections-view right-content">
      <div class="titlebar">Recent Connections</div>
    </div>
  </div>
</template>


<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Leftbar from '@/components/Leftbar.vue'

@Component({
  components: {
    Leftbar,
  },
})
export default class Connections extends Vue {}
</script>


<style lang="scss">
.connections-view {
  .titlebar {
    height: 60px;
  }
}
</style>