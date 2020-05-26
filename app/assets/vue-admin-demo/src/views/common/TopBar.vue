<template>
  <div class="dr-toolbar">
    <div class="option-button el-col-6">
      <!-- TOPBARLEFT -->
    </div>
    <div class="el-col-18">
      <!-- TOPBARRIGHT -->
    </div>
  </div>
</template>
<script>
import { bakUpCMSData } from "@/api/helpCenter";
export default {
  props: {
    device: String,
    pageInfo: Object,
    type: String,
    ids: Array
  },
  data() {
    return {
      selectUserList: [],
      searchkey: ""
    };
  },
  methods: {
    // TOPBARLEFTOPTION
    // TOPBARRIGHTSEARCH
  },
  components: {}
};
</script>
<style lang="scss">
</style>
