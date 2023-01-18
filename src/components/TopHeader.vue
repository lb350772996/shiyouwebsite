<template>
  <div class="Vector1">
    <div class="top">
      <div class="logo">
        <img class="imge1" src="../assets/image1.png">
        <p>沈阳石有贸易有限公司</p>
      </div>
      <div class="line"></div>

        <el-col :span="12">
          <el-dropdown trigger="click">
            <span class="el-dropdown-link">
              <div class="mtopbody" >
                <img src="../assets/Iconlgo.png" alt="">
              </div>
            </span>
            <el-dropdown-menu slot="dropdown" class="downmenu">
              <i trigger="click" class="el-icon-close"></i>
              <el-dropdown-item>
                <div>
                  <p @click="showInfo('ours')">我们的服务</p>
                </div>
              </el-dropdown-item>
              <el-dropdown-item>
                <p @click="showInfo('whomi')">我们是谁</p>
              </el-dropdown-item>
              <el-dropdown-item>
                <p @click="showInfo('bott')">联系</p>
              </el-dropdown-item>
              <el-dropdown-item>
                <p @click="showInfo('datasta')">我们的统计数据</p>
              </el-dropdown-item>
              <div class="dwonline"></div>
              <div class="downimg">
                <img class="imge2" src="../assets/image1.png">
                <p>沈阳石有贸易有限公司</p>
              </div>

            </el-dropdown-menu>
          </el-dropdown>
        </el-col>


      <div class="topbody">
        <div>
          <p @click="showInfo('ours')">我们的服务</p>
        </div>
        <div>
          <p @click="showInfo('whomi')">我们是谁</p>
        </div>
        <div>
          <p @click="showInfo('bott')">联系</p>
        </div>
        <div>
          <p @click="showInfo('datasta')">我们的统计数据</p>
        </div>
      </div>
    </div>
    <div class="m_main">
      <div class="m_left">
        <div class="m_per">
          <div class="m_p_p">每个层面的完美</div>
          <div class="m_d_p">
            <img src="../assets/Line 4.png" alt="">
            <!-- <div class="m_d_p_line"></div> -->
            <div class="m_d_p_p">
              <p class="m_d_p_p1">完美</p>
              <p class="m_d_p_p2">是一种状态，有各种各样的，完整的，无缺陷的，或至善的。这个术语被用来指定一系列不同的，如果经常是相似的概念。这些问题在历史上已经在一些独立的学科中得到了解决。</p>
            </div>
          </div>
        </div>
        <div class="topinto">
          <div class="check">
            <img src="../assets/Icon.png" alt="">
            <p>免费调查</p>
          </div>
          <div class="showinfo">
            <p>查看服务</p>
          </div>
        </div>
        <img src="../assets/swxzch.png" style="margin-top: 32px;" alt="">
      </div>

    </div>
    <div class="main">
      <div class="left">
        <div class="per">每个层面的完美</div>

        <div class="topinto">
          <div class="check">
            <img src="../assets/Icon.png" alt="">
            <p>免费调查</p>
          </div>
          <div class="showinfo">
            <p>查看服务</p>
          </div>
        </div>
      </div>

      <div class="perfer">
        <div class="perline"></div>
        <div class="perinfo">
          <p class="p1">完美</p>
          <p class="p2">是一种状态，有各种各样的，完整的，无缺陷的，或至善的。这个术语被用来指定一系列不同的，如果经常是相似的概念。这些问题在历史上已经在一些独立的学科中得到了解决。
          </p>
        </div>
      </div>
    </div>

  </div>

</template>

<script>
export default {
  name: 'TopHeader',
  methods: {
    showInfo(ours) {
      console.log(ours)
      let toElement = document.getElementById(ours)
      // this.target= targetbox.offsetTop; 
      toElement.scrollIntoView({ block: "start", behavior: "smooth" })
    },
    showTitle() {

    }
  }
}
</script>
<style>

.el-dropdown-menu{
  top: -15px !important;
  left: 150px !important;
  position: relative;
}
.el-dropdown-menu__item p{
  font-size: 16px;
  margin-bottom: 16px;
}
.el-icon-close{
  z-index: 1000;
  position: absolute;
  top: 32px;
  right: 20px;
  font-size: 24px;
  color: #007BFF;
  font-weight: bold;
}
.el-dropdown-menu__item {
  width: 144px;
  text-align: left;
  padding-left: 30px;

}

.downimg {
  display: flex;
  margin-left: 15px;
  gap: 10px;
}

.downmenu {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 33px 20px 33px 40px;


  position: absolute;
  width: 238px;
  height: 320.9px;
  left: 137px;
  top: 0px;

  background: #FFFFFF;
  box-shadow: 0px 4px 4px rgba(88, 100, 105, 0.28);
  border-radius: 0px 0px 0px 20px;
}

.imge2 {
  margin-top: 15px;

  width: 24px;
  height: 24px;

}

.dwonline {
  margin-left: 15px;
  width: 178px;
  height: 0px;

  /* Dark divider */

  border: 1px solid #99AEC8;
  transform: rotate(0.29deg);
}

.el-dropdown-link {
  cursor: pointer;
  color: #409EFF;
}

.el-icon-arrow-down {
  font-size: 12px;
}

.main {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 140px;
}

.m_main {
  display: none;
}

.main .left {
  top: 50px;
  /* width: 50%; */
}

/*
.main .perfer {
  width: 50%;
} */

.p2 {
  width: 454px;
  height: 66px;

  font-family: 'Nunito';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;

  /* Text Grey */

  color: #858484;


  /* Inside auto layout */

  flex: none;
  order: 1;
  flex-grow: 0;
}

.m_main {
  display: none;
}

.p1 {
  width: 82px;
  height: 104px;

  font-family: 'Nunito';
  font-style: normal;
  font-weight: 700;
  font-size: 40px;
  line-height: 55px;

  /* Black */
  margin-top: 0px;
  color: #353E40;


  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
}

.perinfo {
  display: flex;
  flex-direction: row;
  justify-content: center;
  /* align-items: flex-end; */
  padding: 0px;
  margin-top: 110px;
  gap: 16px;
  width: 552px;
  height: 104px;
}

.perline {
  width: 104px;
  height: 0px;

  /* Dark divider */

  border: 1px solid #99AEC8;
  transform: rotate(-90deg);

  /* Inside auto layout */
  margin-top: 150px;
  flex: none;
  order: 0;
  align-self: stretch;
  flex-grow: 0;
}

.perfer {
  display: flex;
  flex-direction: row;
  /* align-items: flex-end; */
  padding: 0px;
  gap: 16px;
  margin-right: 180px;
  /* position: absolute; */
  width: 568px;
  height: 104px;
  left: 749px;
  top: 324px;
}

.showinfo p {
  width: 96px;
  height: 33px;
  margin: auto;
  font-family: 'Nunito';
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 33px;
  /* identical to box height */

  display: flex;
  align-items: center;

  /* Text Grey */

  color: #858484;


  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
}

.showinfo {
  display: flex;
  flex-direction: row;
  align-items: center;
  /* padding: 16px 32px; */
  width: 160px;
  height: 65px;
  background: #FFFFFF;
  border-radius: 8px;

  flex: none;
  order: 1;
  flex-grow: 1;
}

.check img {
  margin: auto;
  width: 24px;
  height: 24px;

  margin-right: 0px;
  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
}

.check p {
  width: 96px;
  height: 33px;
  font-family: 'Nunito';
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 33px;
  margin: auto;
  margin-left: 0px;
  /* identical to box height */
  display: flex;
  /* align-items: center; */
  color: #FFFFFF;
}

.check {
  display: flex;
  flex-direction: row;
  align-items: center;
  /* padding: 16px 32px; */
  gap: 8px;

  width: 192px;
  height: 65px;

  background: #007BFF;
  border-radius: 8px;

  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
}

.topinto {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  margin-top: 28px;
  gap: 40px;

  /* position: absolute; */
  width: 392px;
  height: 65px;
  left: 120px;
  top: 324px;
}

.per {
  font-family: 'Nunito';
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  /* padding-bottom: 180px; */
  line-height: 87px;
  /* margin-right: 180px; */
  color: #353E40;
  /* position: absolute; */
  width: 448px;
  height: 87px;

}

.line {

  width: 395.15px;
  height: 0px;

  /* Dark divider */

  border: 1px solid #99AEC8;

  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
}

.topbody p {

  font-family: 'Nunito';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 150%;
  /* identical to box height, or 24px */

  display: flex;
  align-items: center;

  /* Black */

  color: #353E40;

  flex: none;
  order: 0;
  flex-grow: 0;
}

.topbody div {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 8px 16px;
}

.topbody {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 8px 16px;
  flex: none;
  order: 0;
  flex-grow: 0;
}

/* .topbody{
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 24px;
  width: 496px;
  height: 40px;

  background-color: chartreuse;
  flex: none;
  order: 2;
  flex-grow: 0;
} */
.Vector1 {
  position: absolute;
  width: 100%;
  margin: 0 auto;
  height: 615px;
  left: 0px;
  top: 0px;
  background: linear-gradient(109.5deg, #F0F5F8 29.9%, #DCF3FF 77.69%);
}

.top {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 40px;
  width: 1185.15px;
  height: 47px;
  margin: 0 auto;
  margin-top: 36px;
}

.logo {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 8px;
  width: 214px;
  height: 47px;

  flex: none;
  order: 0;
  flex-grow: 0;

}

.logo p {
  /* 沈阳市石友贸易有限公司 */
  width: 159px;
  height: 19px;

  font-family: 'Nunito';
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 19px;
  /* identical to box height */

  display: flex;
  align-items: center;

  /* Black */

  color: #353E40;


  /* Inside auto layout */

  flex: none;
  order: 1;
  flex-grow: 0;
}

.logo hr {
  width: 395.15px;
  height: 0px;
  border: 1px solid #99AEC8;
  flex: none;
  order: 1;
  flex-grow: 0;
}

.imge1 {
  width: 47px;
  height: 47px;
  /* Inside auto layout */
  flex: none;
  order: 0;
  flex-grow: 0;
}

@media only screen and (max-width:750px) {
  .Vector1 {
    height: 371px;
    width: 100%;
    background-image: url("../assets/Vector\ 3\ \(1\).png");
    background-size: cover;


  }

  .top {
    display: flex;
    flex-direction: row;
    align-items: center;
    /* background-color: #007BFF; */
    padding: 0px;
    gap: 24px;
    width: 335px;
    height: 24px;
  }

  .logo {
    width: 200px;
  }

  .logo img {
    width: 24px;
    height: 24px;
  }

  .logo p {
    font-size: 12px;

  }

  .line {
    width: 99px;
    height: 0px;

    /* Dark divider */

    border: 1px solid #99AEC8;
    transform: rotate(0.29deg);
  }

  .top {
    margin-left: 20px;
    margin-right: 20px;
    gap: 15px;
  }

  .topbody {
    display: none;
  }

  .main {
    display: none;
  }

  .m_main {
    display: flex;
    margin: 0px auto;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    margin-top: 50px;
    gap: 24px;

    width: 335px;
    height: 567px;
  }

  .m_left {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    /* gap: 64px; */

    width: 335px;
    height: 249px;

  }

  .m_per {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 40px;
    margin-bottom: 32px;
    width: 335px;
    height: 131px;

  }

  .m_p_p {
    width: 140px;
    height: 27px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    line-height: 27px;

    /* Black */

    color: #353E40;
  }

  .m_d_p {
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    padding: 0px;
    gap: 16px;

    width: 335px;
    height: 64px;
  }

  .m_d_p_line {
    width: 64px;
    height: 0px;

    /* Dark divider */

    border: 1px solid #99AEC8;
    transform: rotate(-90deg);

    /* Inside auto layout */

    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
  }

  .m_d_p_p {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: flex-start;
    padding: 0px;
    gap: 8px;

    width: 319px;
    height: 64px;
  }

  .m_d_p_p1 {
    width: 28px;
    height: 19px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 19px;
    /* identical to box height */
    margin-top: 0px;

    /* Black */

    color: #353E40;
  }

  .m_d_p_p2 {
    width: 283px;
    height: 64px;
    margin-top: 0px;
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 16px;

    /* Text Grey */

    color: #858484;
  }

  .topinto {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px;
    gap: 40px;

    width: 322px;
    height: 54px;
  }

  .check {
    display: flex;
    flex-direction: row;
    align-items: center;
    /* padding: 16px 32px; */
    gap: 8px;

    width: 154px;
    height: 54px;

    background: #007BFF;
    border-radius: 8px;
    flex: none;
    order: 0;
    flex-grow: 0;
  }

  .check p {
    font-size: 16px;
  }

  .showinfo {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    /* padding: 16px 32px; */

    margin: 0px auto;
    width: 128px;
    height: 54px;

    background: #FFFFFF;
    border: 1px solid #007BFF;
    border-radius: 8px;

  }

  .showinfo p {
    margin-left: 32px;
    font-size: 16px;
  }

}
</style>