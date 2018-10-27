<template>
  <section class="wrap">
    <div class="bg-fixed">
      <img src="../assets/image/bg-a.jpg">
    </div>
    <div class="content">
      <div class="top-content">
        <div class="logoWrap">
          <div class="logo">
            <img src="../assets/image/logo-04.png">
          </div>
        </div>
        <div class="main-desc">
          <h1>壹步之遥，鲜美生活</h1>
          <div class="jump-text">
            <div>
              <p>『壹米优鲜』满足你对生鲜的所有想象</p>
            </div>
          </div>
        </div>
      </div>
      <!-- 选择理由 -->
      <section class="info">
        <p class="info-title">为什么选择“壹米优鲜”？</p>
        <p class="info-sub-title">客户们赞扬，新鲜便捷实惠</p>
        <ul class="info-features">
          <li class="info-feature">
            <div class="info-feature-up">
              <span class="info-feature-up-span info-feature-up-span-1"/>
            </div>
            <div class="info-feature-down">
              <p class="info-feature-down-title">新鲜</p>
              <p class="info-feature-down-content">
                源头直采模式<br>菜品新鲜美味<br>专注所以专业
              </p>
            </div>
          </li>
          <li class="info-feature">
            <div class="info-feature-up">
              <span class="info-feature-up-span info-feature-up-span-2"/>
            </div>
            <div class="info-feature-down">
              <p class="info-feature-down-title">便捷</p>
              <p class="info-feature-down-content">
                一键下单<br>准时到达<br>方便快捷
              </p>
            </div>
          </li>
          <li class="info-feature">
            <div class="info-feature-up">
              <span class="info-feature-up-span info-feature-up-span-3"/>
            </div>
            <div class="info-feature-down">
              <p class="info-feature-down-title">愿景</p>
              <p class="info-feature-down-content">
                让天下的餐厅没有难做的生意<br>让老百姓生活更简单<br>让13亿中国人吃上放心菜
              </p>
            </div>
          </li>
        </ul>
      </section>
      <!-- 壹米优鲜案例 -->
      <div class="success-case">
        <div class="center-wrap">
          <div class="item-title">
            <h2>产品展示<p>Success Case</p></h2>
          </div>
          <div class="item-content">
            <div class="item-cell">
              <div class="img-wrap">
                <img
                  :class="{ img_hover: isBig1 }"
                  src="../assets/image/s_01.jpg"
                  @mouseover="isBig1 = true"
                  @mouseout="isBig1 = false">
              </div>
              <h4>新鲜果蔬</h4>
              <p>Fresh fruit and vegetable</p>
            </div>
            <div class="item-cell">
              <div class="img-wrap">
                <img
                  :class="{ img_hover: isBig2 }"
                  src="../assets/image/s_02.jpg"
                  @mouseover="isBig2 = true"
                  @mouseout="isBig2 = false">
              </div>
              <h4>美味海鲜</h4>
              <p>Delicious seafood</p>
            </div>
            <div class="item-cell">
              <div class="img-wrap">
                <img
                  :class="{ img_hover: isBig3 }"
                  src="../assets/image/s_03.jpg"
                  @mouseover="isBig3 = true"
                  @mouseout="isBig3 = false">
              </div>
              <h4>肉类</h4>
              <p>meat</p>
            </div>
          </div>
        </div>
      </div>
      <!-- 关于我们 -->
      <div class="about-us">
        <div class="about-us-wrap">
          <div class="about-us-left">
            <h2>关于我们
              <p>About us</p>
            </h2>
            <div class="decription">
              <h3>壹米优鲜</h3>
              <p>壹米优鲜（浩海鸿通河北电子商务有限公司）于2018年成立，一直致力于通过互联网的方式来改变农业、农村和农民。
              壹米优鲜独有的“F2B模式”是通过自建仓储、物流、配送，创新升级农产品供应链，砍掉中间环节，一端链接田间地头，一端链接城市，通过自营和合作伙伴，实现农产品从地头到餐桌高速的流通，让利两端，为决胜全面建成小康社会贡献力量。
              同时，利用大数据系统，准确将市场需求反馈给农民，一方面避免了货不对市，另一方面通过解决销路给予了农民安心的保障。专注为全国近千万家餐厅和蔬菜店铺，提供一站式、全品类、全程无忧的农产品采购服务，让天下的餐厅没有难做的生意。此外，壹米优鲜利用自身的渠道优势，要求源头端建立生产标准，保证上行农产品的质量安全，真正实现生产有标准、销路有保障的良性循环。
              通过全面布局，壹米优鲜预计明年覆盖河北省大多数城市。</p>
              <!-- <button class="more-btn">MORE</button> -->
            </div>
          </div>
          <div class="about-us-right">
            <img src="../assets/image/s_04.jpg">
          </div>
          <!-- <div class="modal">
            <ul class="content_list">
              <li>
                <div>
                  <p>
                    <span class='modal-big-font'>1,992</span>
                    <span class='modal-tip'>年</span>
                  </p>
                  <p class='modal-center-text'>成立嘉永</p>
                </div>
              </li>
              <li>
                <div>
                  <p>
                    <span class='modal-big-font'>58</span>
                    <span class='modal-tip'>+</span>
                  </p>
                  <p>年均案列</p>
                </div>
              </li>
              <li>
                <div>
                  <p>
                    <span class='modal-big-font'>50</span>
                    <span class='modal-tip'>+</span>
                  </p>
                  <p>年均热情反馈</p>
                </div>
              </li>
              <li>
                <div>
                  <p>
                    <span class='modal-big-font'>40</span>
                    <span class='modal-tip'>+</span>
                  </p>
                  <p>装修荣誉</p>
                </div>
              </li>
            </ul>
          </div> -->
        </div>
      </div>
      <!-- 成就历程 -->
      <div class="achieve">
        <!-- <div class="achieve-wrap">
          <div class="achieve-item">
            <h3>1998</h3>
            <p>荣入1998上海装修企业</p>
            <p>综合实力150强排名第16位</p>
          </div>
          <div class="achieve-item">
            <h3>2000</h3>
            <p>荣入千禧年上海装修企业</p>
            <p>进入综合实力100强</p>
          </div>
          <div class="achieve-item">
            <h3>2006</h3>
            <p>荣入2006年度中国装修公司</p>
            <p>综合实力100强排名第22位</p>
          </div>
          <div class="achieve-item">
            <h3>2016</h3>
            <p>荣入2016年度上海装修企业</p>
            <p>综合实力100强</p>
          </div>
        </div> -->
      </div>
      <!-- 版权区 -->
      <div class="footer-copyright">
        <div class="footer-wrap">
          <div class="left-title">
            <h3>联系我们</h3>
            <p>Contact US</p>
          </div>
          <div class="right-title">
            <h4>壹米优鲜™ 浩海鸿通河北电子商务有限公司</h4>
            <div class="detail-info">
              <div class="left-detail">
                <div class="detail-item">
                  <span>地址:</span>
                  <span>河北省邢台经济开发区中兴东大街1699号创智园333室</span>
                </div>
                <div class="detail-item">
                  <span>电话:</span>
                  <span>18503223839</span>
                </div>
                <div class="detail-item">
                  <span>邮箱:</span>
                  <span>haohaihongtong@haohaihongtong.com</span>
                </div>
              </div>
            </div>
          </div>
          <div class="real-copy">
            <p>COPYRIGHT (©) 2018 浩海鸿通河北电子商务有限公司</p>
            <p>
              YiMiYouXian Radex HaoHaiHongTong Ecommerce Ltd&nbsp;&nbsp;
              <a
                target="_blank"
                href="http://www.miibeian.gov.cn">冀ICP备18018598号-1</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      isBig1: false,
      isBig2: false,
      isBig3: false
    }
  }
}
</script>

<style lang="stylus">
@import '@/assets/css/main.css'
</style>
