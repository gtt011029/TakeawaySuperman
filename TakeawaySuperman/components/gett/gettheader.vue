<template>
  <div class="cmain">
    <div class="headtop">
      <!--头部左边-->
      <div class="top-left fl">
        <a title="Darry Ring" href="index.html"> <img width="187" height="42" alt="Darry Ring官网" src="../../assets/images/logo.png" /> </a>
        <span style="font-weight: normal;">求婚钻戒领导品牌</span>
      </div>
      <!--头部左边end-->
      <!--头部右边-->
      <div class="top-right fr">
        <!--登录注册-->
        <ul class="tright-ul fl">
          <div id="ucheader1_pllogin1">
            <li>
              <nuxt-link to="/login">登录</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/register">注册</nuxt-link>
            </li>
            <li class="headed">
              <em class="icon shooping"></em><nuxt-link to="/cart">购物车</nuxt-link><i>(0)</i>
            </li>
          </div>
        </ul>
        <!--语言选择-->
        <ul class="langruge-ul fr">
          <li><a target="_blank" href="#">English</a></li>
        </ul>
        <!--搜索框-->
        <div style="display:none;" class="search">
          <input type="text" placeholder="求婚钻戒" class="txt1" />
          <div onClick="showSearch()" class="icon toser">
          </div>
        </div>
      </div>
      <!--头部右边end-->
    </div>
  </div>
</template>

<script>
  export default {
    name: "gettheader"
  }
</script>

<style lang="css">
  @import "@/assets/css/same.css";
  @import "@/assets/css/dr.css";
</style>
