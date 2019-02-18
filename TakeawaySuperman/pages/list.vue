<template>
    <div>
      <gettheader></gettheader>
      <gettnav></gettnav>
      <!--钻戒页面中间-->
      <div class="cort">
        <div class="cmain sp_cort fix">
          <!--背景图-->
          <div class="zj_bk">
            <div class="zbk_top spalid">
              <span>您当前的位置：</span>
              <span id="website_SiteMapPath1">
                <a href="#website_SiteMapPath1_SkipLink"></a><span> <a target="_blank" href="index.html">Darry Ring</a> </span><span> <em>&gt;</em> </span><span> <span>求婚钻戒</span>
                            </span><a id="website_SiteMapPath1_SkipLink"></a></span>
            </div>
            <!--banner中间内容-->
            <div class="zbk_center">
              <!--banner左边-->
              <div class="zbkc-left">
                <h3> 求婚钻戒领导品牌</h3>
                <h2> 男士一生仅能定制一枚</h2>
                <h4> 寓意：一生&middot;唯一&middot;真爱</h4>
                <div class="button">
                  <div id="click" class="bt2">
                    <span>购买资格查询</span>
                  </div>
                  <div id="dzck" class="bt1">
                    <a target="_blank" href="/help/72.html">购买流程说明</a>
                  </div>
                </div>
              </div>
              <!--banner右边的背景图-->
              <div class="zbkc-right">
                <img width="458" height="260" alt="求婚钻戒" src="../assets/images/True-Love-_ring.jpg" />
              </div>
            </div>
          </div>
          <!--背景图end-->
          <!--流程图-->
          <div class="the_lct">
            <img src="../assets/images/lct.png" />
          </div>
          <!--流程图end-->
          <!--小导航-->
          <div class="allchose_nav">
            <!--购买选项-->
            <div class="dr_choose">
              <!--选项nav-->
              <div class="drcho_top">
                <ul class="drchoose_ul">
                  <li class="choose_hover" id="ucser_all"><span>所有</span> </li>
                  <li id="ucser_forever"><span>Forever 系列</span> </li>
                  <li id="ucser_myheart"><span>My Heart 系列</span> </li>
                  <li id="ucser_swear"><span>I Swear系列</span> </li>
                  <li id="ucser_justyou"><span>Just You 系列</span> </li>
                  <li style="background-image:none" id="ucser_truelove"><span>True Love系列</span> </li>
                </ul>
              </div>
              <div class="drcho_bto"></div>
            </div>
            <!--购买选项end-->

            <!--参数选项-->
            <div class="select_choose">
              <div class="thefirst_it">
                <div class="search2 search_other fr">
                  <input type="text" placeholder="产品名称/关键字" class="txt2" id="txtTitle" name="txtTitle" />
                  <div id="prosearch" class="icon toser2"></div>
                </div>
                <div class="fl">
                  <span>价格：</span>
                  <select id="drpListPrice" name="drpListPrice">
                    <option value="-1" selected="selected">不限</option>
                    <option value="1">5000以下</option>
                    <option value="2">5000-10000</option>
                    <option value="3">10000-20000</option>
                    <option value="4">20000以上</option>
                  </select>
                  <span>钻石：</span>
                  <select id="drplistzct" name="drplistzct">
                    <option value="-1" selected="selected">不限</option>
                    <option value="1">10分以下</option>
                    <option value="2">10分-30分</option>
                    <option value="3">30分-50分</option>
                    <option value="4">50分-1克拉</option>
                    <option value="5">1克拉以上</option>
                  </select>
                  <span>材质：</span>
                  <select id="drpListCZ" name="drpListCZ">
                    <option value="-1" selected="selected">不限</option>
                    <option value="1">PT950</option>
                    <option value="2">18K白金</option>
                    <option value="3">18K黄金</option>
                    <option value="4">18K玫瑰金</option>
                  </select>
                </div>
                <div style="display:none" id="btncz" class="choose_cz fl">
                  <span>重 置</span>
                </div>
                <div class="choose_serach fl" style="display:none">
                  <a target="_blank" href="/diydr/"><span>高级搜索</span></a>
                </div>
                <span style="display:none" id="spanclick"></span>
                <div style="display:none" class="choose-ks fr">
                  <span id="xp"><i>新品</i> <em></em></span>
                  <span id="xl"> <i>销量</i> <em></em></span>
                  <span id="jg"><i>价格</i> <em></em></span>
                </div>
              </div>
              <div class="thesec_it">
                <div class="thesec_word fr">
                  <span>共<i>76</i>件商品</span>
                  <span> <i class="thered_color">1</i>/5 </span>
                  <em onClick="getPage('up')" class="no_paget" id="em_up">上一页</em><em class="" onClick="getPage('down')" id="em_down">下一页</em>
                  <span style="display:none" id="lbCurrent">1</span>
                  <span style="display:none" id="lbTot">5</span>
                  <input type="submit" style="display:none" id="btnUp" value="上一页" name="btnUp" />
                  <input type="submit" style="display:none" id="btnNext" value="下一页" name="btnNext" />
                </div>
                <div class="thesec_word-left fl">
                  <span>排序：</span>
                  <b> <i id="i_rq">按人气</i> <i id="i_xl">按销量</i> <i id="i_jg">按价格</i> </b>
                </div>
              </div>
            </div>
            <!--参数选项end-->
          </div>
          <!--小导航end-->
          <!--高级搜索-->
          <!--高级搜索end-->
          <!--购买的款式-->
          <div class="cmain">
            <ul class="buyit">
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Forever系列 经典款&nbsp;50分&nbsp;H色" src="../assets/images/2014090119350717386d7a1e.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/201409011935072849fe802f.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/78.html">DR钻戒 Forever系列 经典款&nbsp;50分&nbsp;H色</a></p>
                  <p> <span>￥25,700</span><i>销量：5698</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="/darry_ring/387.html"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 True Love系列 典雅&nbsp;40分&nbsp;F色" src="../assets/images/201412081512070b82d519cb.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20141208151207e3fa9cdc9e.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/387.html">DR钻戒 True Love系列 典雅&nbsp;40分&nbsp;F色</a></p>
                  <p> <span>￥19,150</span><i>销量：2654</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one" style="opacity: 1;">
                    <img width="236px" height="236" alt="DR钻戒 Forever系列  简奢款&nbsp;30分&nbsp;F色" src="../assets/images/201412081516238b52b39cab.jpg" />
                  </div>
                  <div class="bything-two" style="opacity: 0;">
                    <img width="236px" height="236" src="../assets/images/20141208151624bd02fe9e65.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/379.html">DR钻戒 Forever系列 简奢款&nbsp;30分&nbsp;F色</a></p>
                  <p> <span>￥12,200</span><i>销量：2136</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Marry Me  纯爱&nbsp;40分&nbsp;H色" src="../assets/images/201412031648134faa47945e.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20141203164814cbaa761ecb.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/389.html">DR钻戒 Marry Me 纯爱&nbsp;40分&nbsp;H色</a></p>
                  <p> <span>￥13,900</span><i>销量：1986</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 My heart系列 奢华款&nbsp;70分&nbsp;H色" src="../assets/images/201502031541470f549eecb4.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/2015020315414939f8806bca.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/168.html">DR钻戒 My heart系列 奢华款&nbsp;70分&nbsp;H色</a></p>
                  <p> <span>￥38,636</span><i>销量：2708</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Believe系列 典雅&nbsp;30分&nbsp;H色" src="../assets/images/2015012911164499edc9d9cc.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20150129111645f4a722d817.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/161.html">DR钻戒 Believe系列 典雅&nbsp;30分&nbsp;H色</a></p>
                  <p> <span>￥10,600</span><i>销量：1967</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 My heart系列 简奢款&nbsp;30分&nbsp;H色" src="../assets/images/20141208151342d086aedadc.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20141208151343c33b1c06ce.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/329.html">DR钻戒 My heart系列 简奢款&nbsp;30分&nbsp;H色</a></p>
                  <p> <span>￥14,820</span><i>销量：975</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Just you系列 经典款&nbsp;25分&nbsp;I-J色" src="../assets/images/20141208151441cc5ac80d54.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20141208151441a7c5365eda.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/383.html">DR钻戒 Just you系列
                    经典款&nbsp;25分&nbsp;I-J色</a></p>
                  <p> <span>￥5,228</span><i>销量：1263</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Forever系列 经典款&nbsp;40分&nbsp;D色" src="../assets/images/201409011932585de1c2f2a9.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20140901193258beafcb5eb7.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/87.html">DR钻戒 Forever系列 经典款&nbsp;40分&nbsp;D色</a></p>
                  <p> <span>￥15,800</span><i>销量：2413</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Just you系列 经典款&nbsp;20分&nbsp;I-J色" src="../assets/images/201409031759476e8527cccb.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20140903175947fa15145af3.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/335.html">DR钻戒 Just you系列
                    经典款&nbsp;20分&nbsp;I-J色</a></p>
                  <p> <span>￥4,699</span><i>销量：1320</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Forever系列 经典款&nbsp;30分&nbsp;E色" src="../assets/images/2014090119253914614d2d7b.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/2014090119253961c1aa6a86.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/150.html">DR钻戒 Forever系列 经典款&nbsp;30分&nbsp;E色</a></p>
                  <p> <span>￥9,800</span><i>销量：2034</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 I Swear系列 奢华款&nbsp;40分&nbsp;H色" src="../assets/images/201504251408518eddbc7a98.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20150425140852a0a0f1e3e2.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/388.html">DR钻戒 I Swear系列 奢华款&nbsp;40分&nbsp;H色</a></p>
                  <p> <span>￥20,600</span><i>销量：1064</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 True Love系列 简奢款&nbsp;30分&nbsp;E色" src="../assets/images/2014091515351160b3d26880.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20140901162336bad2605031.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/347.html">DR钻戒 True Love系列
                    简奢款&nbsp;30分&nbsp;E色</a></p>
                  <p> <span>￥11,000</span><i>销量：1235</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 True Love系列 简奢款&nbsp;30分&nbsp;E色" src="../assets/images/2014091515351160b3d26880.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20140901162336bad2605031.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/347.html">DR钻戒 True Love系列
                    简奢款&nbsp;30分&nbsp;E色</a></p>
                  <p> <span>￥11,000</span><i>销量：1235</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 Forever系列 经典款&nbsp;100分&nbsp;J色" src="../assets/images/201409031259093e45b5ecf0.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/2014090312590972b221c6ce.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/333.html">DR钻戒 Forever系列 经典款&nbsp;100分&nbsp;J色</a></p>
                  <p> <span>￥64,700</span><i>销量：1387</i></p>
                </div>
              </li>
              <!--每一个款式-->
              <li>
                <div class="by_top">
                  <a target="_blank" href="#"></a>
                  <div class="bything-one">
                    <img width="236px" height="236" alt="DR钻戒 My heart系列 简奢款&nbsp;20分&nbsp;H色" src="../assets/images/20141208151356816302d93c.jpg" />
                  </div>
                  <div class="bything-two">
                    <img width="236px" height="236" src="../assets/images/20141208151356af0991c81c.jpg" />
                  </div>
                </div>
                <div class="by_center">
                </div>
                <div class="by_bottom">
                  <p> <a target="_blank" href="/darry_ring/170.html">DR钻戒 My heart系列 简奢款&nbsp;20分&nbsp;H色</a></p>
                  <p> <span>￥8,520</span><i>销量：1484</i></p>
                </div>
              </li>
            </ul>
            <!--购买的款式end-->
          </div>

          <div class="paging_all" id="pageing_pagingDiv">
            <div class="paging_all-cort">
              <ul class="paging fl">
                <li class="pli pag_gray">&lt;&lt;上一页</li>
                <li class="pag_gray">1</li>
                <li>2</li>
                <li>3</li>
                <li>4</li>
                <li>5</li>
                <li class="pli2">下一页&gt;&gt;</li>
              </ul>
              <p class="pag_p fl"> <span>共5页，到第</span> <input type="text" class="pag_txt" id="pageing_pag_txt"
                                                              name="pageing$pag_txt" />页 <input type="button" class="pag_bt" onClick="__CurrentPaging.PageIndexChaned($('#pageing_pag_txt').val());$('#pageing_pag_txt').val('');"
                                                                                                value="确定" /> </p>
            </div>
          </div>
          <!--分页end-->
          <!--分页end-->
      </div>
      </div>
      <gettfooter></gettfooter>
    </div>
</template>

<script>
  import gettfooter from  "../components/gett/gettfooter.vue"
  import gettheader from  "../components/gett/gettheader.vue"
  import gettnav from  "../components/gett/gettnav.vue"
    export default {
        name: "list",
        components:{
          gettfooter,
          gettheader,
          gettnav,
        }
    }
</script>

<style scoped>

</style>
