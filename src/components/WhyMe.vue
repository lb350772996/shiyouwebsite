<template>
<div class="memian">
    <img class="mainimg" src="../assets/Ellipse 6.png" alt="">
    <img class="mainimg b7"  src="../assets/Ellipse 7.png" alt="">
    <img class="mainimg b8"  src="../assets/Ellipse 8.png" alt="">
    <img class="mainimg b9"  src="../assets/Ellipse 9.png" alt="">
    <img class="mainimg b4"  src="../assets/Ellipse 4.png" alt="">
    <img class="mainimg b5"  src="../assets/Ellipse 5.png" alt="">
    <img class="mainimg mb5" src="../assets/Ellipse 4 (1).png" alt="">
    <img class="mainimg mb6" src="../assets/Ellipse 5 (1).png" alt="">
    <img class="mainimg mb10" src="../assets/Ellipse 10.png" alt="">
    <img class="mainimg mb11" src="../assets/Ellipse 6 (1).png" alt="">
    <img class="mainimg mb12" src="../assets/Ellipse 11.png" alt="">
    <div class="whymian">
        <div class="whyme">
            <div class="whetitle">
                <p class="wp">为什么选择我们？</p>
                <div class="whyeline"></div>
            </div>
            <div class="whylist">
                <div class="whylist_1">   
                    <div class="whyinfo">
                        <img src="../assets/tool-02.png" alt="">
                        <div class="whytoolinfo">
                            <div class="whytoolinfop1">技术服务</div>
                            <div class="whytoolinfop2">安全是指免受或抵御来自外部力量的潜在伤害或其他不想要的强制性变化。</div>
                        </div>
                    </div>
                    <div class="whyinfo">
                        <img class="if_mg_1" src="../assets/Icon (2).png" alt="">
                        <div class="whytoolinfo">
                            <div class="whytoolinfop1">技术开发</div>
                            <div class="whytoolinfop2">安全是指免受或抵御来自外部力量的潜在伤害或其他不想要的强制性变化。</div>
                        </div>
                        <img class="if_mg_2" src="../assets/Icon (2).png" alt="">
                    </div>  
                </div>
           
                <div class="whylist_1">
                    <div class="whyinfo">
                        <img src="../assets/Icon (1).png" alt="">
                        <div class="whytoolinfo">
                            <div class="whytoolinfop1">技术服务</div>
                            <div class="whytoolinfop2">安全是指免受或抵御来自外部力量的潜在伤害或其他不想要的强制性变化。</div>
                        </div>
                    </div>
                    <div class="whyinfo">
                        <img class="if_mg_1" src="../assets/Icon (3).png" alt="">
                        <div class="whytoolinfo">
                            <div class="whytoolinfop1">技术交流</div>
                            <div class="whytoolinfop2">安全是指免受或抵御来自外部力量的潜在伤害或其他不想要的强制性变化。</div>
                        </div>
                        <img class="if_mg_2" src="../assets/Icon (3).png" alt="">
                    </div>  
                </div>
            </div>  

            
        </div>
        
    </div>
</div>

    

</template>
<script>
export default {
  name: 'WhyMe'
}
</script>
<style>
.if_mg_2{
    display: none;
}
.whymian{
    position: relative;
    z-index: 2;
}
.mainimg{
    position: absolute;
    z-index: 1;
    top: 135px;
}
.b7{
    top: 30px;   
    left: 0px;
}
.b8{
    top: 460px;   
    left: 40px;
}
.b9{
    top: 360px;   
    left: 700px;
}
.b4{
    top: 80px;   
    left: 1250px;
}
.b5{
    top: 50px;   
    left: 1350px;
}
.whytoolinfop2{
    width: 282px;
    height: 44px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 22px;

    /* Text Grey */

    color: #858484;
}
.whytoolinfop1{
    width: 96px;
height: 33px;

font-family: 'Nunito';
font-style: normal;
font-weight: 600;
font-size: 24px;
line-height: 33px;
/* identical to box height */


/* Black */

color: #353E40;

}
.whytoolinfo{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;

    width: 282px;
    height: 93px;
}
.whyinfo{
    /* Auto layout */
    background-color: coral;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 48px 54px;
    gap: 40px;

    width: 490px;
     height: 54px; 

    background: #FFFFFF;
    border-radius: 20px;

    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
}
.whylist_1{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 16px;

    width: 490px;
    height: 394px;


    /* Inside auto layout */

    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}
.wp{
    width: 299px;
    height: 55px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 35px;
    line-height: 55px;
    /* identical to box height */

    margin-bottom: 0px;
    /* Black */

    color: #353E40;


    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;
}
.whylist{
    /* Auto layout */
    /* background-color: blueviolet; */
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 0px;
    gap: 160px;
    margin-top: 40px;
    width: 1140px;
    height: 394px;


    /* Inside auto layout */

    flex: none;
    order: 1;
    flex-grow: 0;
}
.whyeline{
    /* Line 4 */
    width: 200px;
    height: 0px;
    /* Dark divider */
    border: 1px solid #99AEC8;
    /* Inside auto layout */
    flex: none;
    order: 1;
    flex-grow: 0;
}
.whetitle{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px 0px 0px 45px;
    gap: 20px;

    width: 1200px;
    height: 75px;

    /* Inside auto layout */

    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
} 
.whymain{
    /* background-color: cadetblue; */
    margin-top: 1500px;
    width: 1440px;
    height: 626px;
}

.whyme{
    /* background-color:aqua; */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0px;
    gap: 40px;
    margin-top: 50px;
    margin-left: 200px;
    width: 1200px;
    height: 509px;
    margin: 150px auto;
}
.memian{
    width: 1440px;
    height: 626px;
    background: #F9F9F9;
    margin: 0px auto;
    position: relative;
}

@media only screen and (max-width:750px) {
    .memian{
        /* background-color: aqua; */
        top: 40px;
        margin-bottom: 40px;
        width: 100%;
    }
    .whyme{
        margin-left: 0px;
        margin-right: 0px;
        width: 335px;
        gap: 0px;
    }
    .whylist{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
        gap: 24px;
        margin-left: 20px;
        width: 335px;
        margin-top: 0px;
        height: 676px;
    }
    .whyinfo{
        width: 335px;
        margin-left: 50px;
        padding: 32px 18px;
    }
    .whylist_1{
        height: 250px;
        width: 335px;
    }
    .mainimg{
        display: none;
    }
    .mb5{
        display: flex;
        left: 256px;
        top:-12px
    }
    .mb6{
        display: flex;
        left: 320px;
        top:-45px
    }

    .mb10{
        display: flex;
        left: 4px;
        top:12px
    }
    .mb11{
        display: flex;
        left: 140px;
        top:500px
    }
    .mb12{
        display: flex;
        left: 300px;
        top:545px
    }

    .whytoolinfop2{
        width: 250px;
        font-size: 14px;
    }
    .whyinfo img{
        margin-top: 20px;
    }
    .if_mg_2{
        display: flex;
    }
    .if_mg_1{
        display: none;
    }
    .memian{
        width:335 px;
    }
    .whomi{
        width: 335px;
    }
    .whoinfo{
        width: 335px;
    }
   .whetitle{
    width: 100%;
   }

   
    .whop2{
        width: 335px;
    }
}
</style>