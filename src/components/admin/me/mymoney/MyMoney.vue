<template>
    <div style="width: 90%">
      <h3 style="float: left">账户信息</h3>
      <hr style="margin-top: 80px">
      <avatar style="float: left"></avatar>
      <section class="box" style="float: left;margin-left: 20px;background-color: white">
        <p style="float: left;color: black">账户余额（元）: &nbsp;{{balance}}</p><br>
        <div class="clear"></div>
        <p style="float: left;color: black">赠券，专用卡等余额(元): &nbsp;&nbsp;{{coupon}}</p>
        <div class="clear"></div>
      </section>
    </div>
</template>
<style scoped>

</style>
