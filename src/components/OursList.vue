<template>
    <div class="ours" id="ours">
        <div class="ourstitle">
          <p>我们的服务</p>
          <div class="oursline"></div>
        </div>

        <div class="ourslist">
          <div class="oursinfo">
            <img src="../assets/Group 8.png" alt="">
            <div class="oursinfob">
              <p class="oursp1">日常百货服务</p>
              <p class="oursp2">商业计划是对企业未来的书面描述，是一份告诉你计划做什么的文件</p>
            </div>
          </div>
          <div class="oursinfo">
            <img src="../assets/Group 8 (2).png" alt="">
            <div class="oursinfob">
              <p class="oursp1">五金产品零售</p>
              <p class="oursp2">最近，这份榜单上的商业创意越来越受欢迎，都是从工作中开始的。</p>
            </div>
          </div>
          <div class="oursinfo">
            <img src="../assets/Group 9.png" alt="">
            <div class="oursinfob">
              <p class="oursp1">机械零件</p>
              <p class="oursp2">SEO是使内容在自然或有机的搜索结果中排名靠前的关键。</p>
            </div>
          </div>
          <div class="oursinfo">
            <img src="../assets/Group 8 (1).png" alt="">
            <div class="oursinfob">
              <p class="oursp1">机械设备销售</p>
              <p class="oursp2">创造性的指导通常是通过实践和指导来学习的。</p>
            </div>
          </div>
          <div class="oursinfo">
            <img src="../assets/Group 8 (3).png" alt="">
            <div class="oursinfob">
              <p class="oursp1">日常百货服务</p>
              <p class="oursp2">商业计划是对企业未来的书面描述，是一份告诉你计划做什么的文件</p>
            </div>
          </div>
          <div class="oursinfo">
            <img src="../assets/Group 8 (4).png" alt="">
            <div class="oursinfob">
              <p class="oursp1">日常百货服务</p>
              <p class="oursp2">商业计划是对企业未来的书面描述，是一份告诉你计划做什么的文件</p>
            </div>
          </div>
          
        </div>
    </div>
</template>
<script>
export default {
  name: 'OursList'
}
</script>
<style>
.oursp1{
  width: 151px;
  height: 33px;
  margin-top: 0px;
  margin-bottom: 0px;
  font-family: 'Nunito';
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 33px;
  color: #353E40;
  text-align: center;
}
.oursp2{
  width: 282px;
  height: 44px;
  margin-top: 0px;
  margin-bottom: 0px;

  font-family: 'Nunito';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;

  color: #858484;

}
.oursinfob{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0px;
  gap: 16px;

  width: 282px;
  height: 93px;

}
.oursinfo{
  /* background-color: blueviolet; */
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  gap: 31px;

  width: 282px;
  height: 235px;
}
.ourslist{
  /* background-color: brown; */
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;
  gap: 50px 160px;

  width: 1200px;
  height: 532.01px;
  flex-direction: row;
  flex-flow: wrap;

  /* Inside auto layout */

  flex: none;
  order: 1;
  flex-grow: 0;
}
.oursline{
  width: 200px;
  height: 0px;

  /* Dark divider */

  border: 1px solid #99AEC8;

  /* Inside auto layout */

  flex: none;
  order: 1;
  flex-grow: 0;
}
.ourstitle p{
  margin-top: 0px;
  margin-bottom: 0px;
  width: 209px;
  height: 51px;

  font-family: 'Nunito';
  font-style: normal;
  font-weight: 700;
  font-size: 40px;
  line-height: 55px;
  /* Black */

  color: #353E40;


  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
}
.ourstitle{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px 0px 0px 78px;
  gap: 20px;
  margin: 0px auto;
  width: 1200px;
  height: 71px;
  /* Inside auto layout */

  flex: none;
  order: 0;
  align-self: stretch;
  flex-grow: 0;
}
.ours{
  /* background-color: chartreuse; */
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-left: 200px;
  padding: 0px;
  gap: 40px; 
  margin-top: 660px;
  /* position: absolute; */
  width:  100%;
  height: 643px;

  margin: 660px auto;
  margin-bottom: 0px;

}
@media only screen and (max-width:750px) {
  .ours{
    margin-top: 770px;
    width: 100%;
  }
  .ourstitle{
    padding-left: 20.5px;
      width:334px;;
  }
  .ourslist{
    width:334px;;
    gap: 32px 32px;
  }
  .oursinfo{
    width: 150px;
  height: 162px;
  gap: 16px;
  }
  .oursinfo img{
    width: 68px;
    height: 68px;
  }
  .oursinfob{
    width: 150px;
height: 48px;
  }

  .oursp1{
    font-size: 16px;
    line-height: 22px;
  }
  .oursp2{
    font-size: 12px;
line-height: 16px;
width: 150px;
height: 32px;
  }
}
</style>