<template>
  <div>
    <van-nav-bar
      title="支付信息"
      left-text="返回"
      left-arrow
      @click-left="onClickLeft"
    />
    <div class="text">welcome to jetsod</div>
  </div>
</template>

<script>
  export default {
    name: "Payment",
    methods: {
      onClickLeft() {
        this.$router.push({ path: '/account' })
      }
    },
  }
</script>

<style scoped>
.text {
  text-align: center;
}
</style>