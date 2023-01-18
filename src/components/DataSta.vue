<template>
    <div class="datasta" id="datasta">
        <div class="stamain">
            <div class="stalef"><p>我们的统计数据</p> <div class="staline"></div></div>
            <div class="stamid">
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">400</p>
                        <p class="stanum2">+</p>
                    </div>
                    <p class="stanum3">完成项目</p>
                </div>
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">1,250</p>
                        <p class="stanum2">+</p>
                    </div>
                    <p class="stanum3">咖啡杯</p>
                </div>
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">5, 630</p>
                        <p class="stanum2">+</p>
                    </div>
                    <p class="stanum3">有效的客户</p>
                </div>
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">300</p>
                        <p class="stanum2">+</p>
                    </div>
                    <p class="stanum3">奖</p>
                </div>
            </div>
        </div>
        <p class="stashow">统计学是数学的一个分支，研究数字事实的收集、分类、分析和解释，以便在数据的可量化似然概率的基础上得出推论。</p>
        <div class="stamid_c">
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">400</p>
                        <p class="stanum2">+</p>
                        <p class="stanum3">完成项目</p>
                    </div>
                    
                </div>
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">1,250</p>
                        <p class="stanum2">+</p>
                           <p class="stanum3">咖啡杯</p>
                    </div>
                 
                </div>
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">5, 630</p>
                        <p class="stanum2">+</p>
                            <p class="stanum3">有效的客户</p>
                    </div>
                
                </div>
                <div class="stainfo">
                    <div class="stanum">
                        <p class="stanum1">300</p>
                        <p class="stanum2">+</p>
                          <p class="stanum3">奖</p>
                    </div>
                  
                </div>
            </div>
    </div>
</template>
<script>
export default {
  name: 'DataSta'
}
</script>
<style>
.stashow{
    width: 284px;
    height: 57px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 19px;

    /* Text Grey */

    color: #858484;
    
}
.stanum3{
margin-top: 0px;
/* width: 64px; */
height: 22px;

font-family: 'Nunito';
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 22px;
/* identical to box height */


/* Text Grey */

color: #858484;
}
.stanum2{
    width: 24px;
    height: 55px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 55px;
    /* identical to box height */
    margin-bottom: 0px;
    margin-top: 35px;
    letter-spacing: -0.01em;

    /* Active */

    color: #007BFF;
}
.stanum1{
    /* width: 86px; */
    height: 65px;
    margin-top: 30px;
    margin-bottom: 0px;
    /* margin-top: 20px; */
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 48px;
    line-height: 65px;
    letter-spacing: -0.01em;

    /* Black */

    color: #353E40;

}
.stanum{
    margin-top: 0px;
    margin-bottom: 0px;
    display: flex;
}
.staline{
    width: 80px;
    height: 0px;

/* Dark divider */

border: 1px solid #99AEC8;
}
.stalef p{
    width: 280px;
    height: 55px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 55px;
    /* identical to box height */


    /* Black */

color: #353E40;
}
.stamain{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 16px;

    width: 1168px;
    height: 91px;
}
.stamid{
    display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 64px;

width: 756px;
height: 91px;
/* background-color: bisque; */
}
.stalef{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 16px;

    width: 396px;
    height: 55px;
    /* background-color: bisque; */
}
.datasta{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    /* gap: 40px; */
    width: 1200px;
    height: 192px;
    margin: 0px auto;
    /* background-color: aquamarine; */
}
.stamid_c{
    display: none;
}
@media only screen and (max-width:750px) {
    .datasta{
        width: 100%;
        height: 593px;
        padding-left: 35px;
    }
    .stainfo{
    width: 100%;
   
    }
    .stalef{
        width: 335px;
    }
    .stanum{
        gap: 8px;
    }
    .stanum3{
        margin-top: 52px;
        height :22px
    }
    .stanum{
        widows: 335px;
    }
    .staline{
        display: none;
    }
    .stamid{
        display: none;
    }
    .stamid_c{
        display: block;
    }
    .stamain{
        width: 100%;
    }
}
</style>