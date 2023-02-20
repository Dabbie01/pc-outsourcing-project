<!--
 * @Author: Dabbie 2310734576@qq.com
 * @Date: 2022-05-08 09:23:18
 * @LastEditors: Dabbie 2310734576@qq.com
 * @LastEditTime: 2023-02-20 15:47:14
 * @FilePath: \vue-xhc-master\src\components\aboutxhc\aboutxhc-head\aboutxhc-head.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div>
    <section id="home">
      <div
        class="logo-wrapper"
      >
        <img
          src="~@/assets/gowhere.png"
          alt=""
          style="width: 80px; height: 60px"
        />
      </div>
      <div class="container">
        <div>
          <div>
            <h1>我们相信科技是生命的第一创造力</h1>
            <div class="divider"></div>
            <h4>我们以前沿的生化科学及技术研究为企业生命力,</h4>
            <h4>探索并攻克严重疾病治愈的疗法，</h4>
            <h4>重新点燃患者生命之光。</h4>
          </div>
        </div>
        <div>
          <a href="#" class="btn btn-default">查看更多</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style>
/*home start*/
#home {
  width: 100%;
  height: 100vh;
  background: url("~@/assets/home.jpg") no-repeat 50% 20% fixed;
  position: relative;
  color: white;
  display: flex;
  align-items: center;
  text-align: center;
}

#home .logo-wrapper {
  background-color: rgba(255, 255, 255, 0.3);
  position: absolute;
  left: 40px;
  top: 40px;
  padding: 10px;
}

#home .divider {
  width: 50%;
  height: 1px;
  background-color: white;
  display: inline-block;
}
#home h1 {
  font-size: 40px;
  letter-spacing: 9px;
  padding: 10px;
}
#home h2 {
  font-size: 30px;
  letter-spacing: 9px;
  padding: 10px;
}
#home h4 {
  font-size: 20px;
  padding: 5px;
}
#home .btn {
  background-color: #37b7e5;
  padding: 7px 20px;
  border-radius: 0px;
  font-family: pinghei-light;
  font-size: 16px;
  border: 4px #37b7e5 solid;
  color: white;
  transition: all 1s;
  position: relative;
  vertical-align: middle;
  top: 30px;
}

#home .btn:hover {
  background-color: transparent;
  color: #37b7e5;
}
/*home end*/
</style>
