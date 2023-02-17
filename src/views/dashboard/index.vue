<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      程序员之家博客管理系统
    </div>
    <div>
      欢迎关注范雷的gitee账号：<a style="color: red;margin-right: 60px" href="https://gitee.com/PangLeDD">https://gitee.com/PangLeDD</a>PangLeDD
    </div>
    <H3>
      欢迎 !  使用程序员之家博客系统后台管理功能
    </H3>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
