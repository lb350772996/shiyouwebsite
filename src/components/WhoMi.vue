<template>
    <div class="whomi" id="whomi">
        <div class="whomitopc"><p >我们是谁？</p> <div class="wholine_c"></div></div>
        <div class="whoinfo_c">
            <img class="mi_img1" src="../assets/Image Placeholder.png" alt="">
            <div> <p class="whop1">沈阳市石友贸易有限公司成立于2022年08月04日，注册地位于辽宁省沈阳市和平区南堤西路369号1门A092，法定代表人为宋杰。</p> 
                 <p class="whop2">经营范围包括一般项目：日用百货销售，五金产品零售，机械零件、零部件销售，化工产品销售（不含许可类化工产品），机械设备销售，金属制品销售，办公设备销售，农、林、牧、副、渔业专业机械的销售，电工器材销售，建筑装饰材料销售，金属材料销售，润滑油销售，第一类医疗器械销售，国内贸易代理，农副产品销售，饲料原料销售，货物进出口，技术进出口，销售代理，家用电器销售，金属矿石销售，塑料制品销售，橡胶制品销售，新能源汽车电附件销售，电气设备销售，通讯设备销售，劳动保护用品销售，家具零配件销售，日用品销售，软件开发，技术服务、技术开发、技术咨询、技术交流、技术转让、技术推广（除依法须经批准的项目外，凭营业执照依法自主开展经营活动）</p>
            </div>
            <img src="../assets/image 11(1).png" alt="" class="mi_img2"> 
        </div>
    </div>
</template>
<script>
export default {
  name: 'WhoMi'
}
</script>
<style>
.mi_img2{
    display: none;
}
.whop2{
    width: 431px;
    height: 209px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 19px;

    /* Text Grey */

    color: #858484;
}
.whop1{
    width: 431px;
height: 66px;

font-family: 'Nunito';
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 22px;

/* Black */

color: #353E40;
}
.whoinfo_c{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 80px;
    margin-left: 39px;
    width: 345px;
    height: 326px;
    flex-wrap: wrap;

    /* Inside auto layout */

    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
    /* background-color: brown; */
}
.wholine_c{
    width: 200px;
    height: 0px;
    margin-left: 39px;
    /* Dark divider */

    border: 1px solid #99AEC8;

    /* Inside auto layout */

    flex: none;
    order: 1;
    flex-grow: 0;
}
.whomitopc p{
    width: 179px;
    height: 51px;
    /* margin-top: 77px; */
    margin-left: 39px;
    margin-bottom: 0px;
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 35px;
    line-height: 55px;

    /* Black */

    color: #353E40;


    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
}
.whomitopc{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 24px;

    width: 200px;
    height: 75px;


    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
}
.whomi{
    display: flex;
    /* background-color: aqua; */
    /* position: absolute; */
    width: 1200px;
    height: 698px;
    margin: 240px auto;
    background: #F9F9F9;
    border-radius: 20px 129px 20px 20px;
    flex-flow: wrap;
    margin-bottom: 0px;
    margin-top: 0px;
}
@media only screen and (max-width:750px) {
    .mi_img1{
        display: none;
    }
    .mi_img2{
        display: flex;
    }
    .whomitop{
        width: 335px;
    }
    .whomitopc p{
        margin-left: 0px;
    }
    .wholine_c{
        margin-left: 0px;
    }
    .whoinfo_c{
        margin-left: 0px;
        height: 726px;
        gap: 20px;
    }
    .whomi{
        height: 826px;
        width: 100%;
     
    }
    .whop1{
        width: 335px;
        height: 66px;
        margin-left: 0px;
        font-family: 'Nunito';
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 22px;

        /* Black */

        color: #353E40;
    }
}
</style>