<template>
    <div class="bott" id="bott">
        <div class="btitle">
            <div class="botlogo">
                <img src="../assets/image1.png" alt="">
                <p>沈阳市石友贸易有限公司</p>
                <div class="botline"></div>
                
            </div>
            
        </div>
        <div class="botinfo">
            <div class="botinfoleft">
                <p>沈阳市石友贸易有限公司成立于2022年08月04日</p>
                <p>注册地位于辽宁省沈阳市和平区南堤西路369号1门A092</p>
                <p>法定代表人为宋杰</p>
            </div>
            <div class="botinforight">
                <div class="botrighta">
                    <p class="bottitle">我们的公司</p>
                    <!-- <div class="botrightinfo"> -->
                        <p class="botrightinfop">首页</p>
                        <p class="botrightinfop">联系</p>
                    <!-- </div> -->
                </div>
                <div class="botrighta">
                    <p class="bottitle">订阅和遵循</p>
                    <div class="botmid">

                        <img src="../assets/facebook logo.png" alt="">
                        <img src="../assets/Vector.png" alt="">
                    </div>
                </div>
                <div class="botrightb">
                    <p class="bottitle">订阅简报</p>
                    <div class="botemail">
                        <p>Email</p>
                        <img src="../assets/mail-02.png" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="botfin">
            <div class="finline"></div>
            <div class="fininfo">
                <p>Copyright © 2022.</p>
            </div>
        </div>
    </div>

</template>
<script>
export default {
  name: 'SyBott'
}
</script>
<style>
.fininfo p{
    /* width: 101px; */
    height: 16px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 16px;

    /* Black */

    color: #353E40;


    /* Inside auto layout */

    flex: none;
}
.fininfo{
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 10px;
    gap: 10px;

    width: 121px;
    height: 36px;


    /* Inside auto layout */

    flex: none;
}
.finline{
    width: 1200.01px;
    height: 0px;

    /* Dark divider */

    border: 1px solid #99AEC8;

    /* Inside auto layout */

    flex: none;
}
.botfin{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 4px;

    width: 1200.01px;
    height: 40px;
    order: 3;
    flex: none;
}
.botemail{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    /* padding: 8px 16px; */
    gap: 80px;

    width: 287px;
    height: 32px;

    /* White */

    background: #FFFFFF;
    /* White */

    border: 1px solid #FFFFFF;
    border-radius: 20px;

    /* Inside auto layout */

    flex: none;
    }
.botrightb{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 8px;

    width: 287px;
    height: 78px;


    /* Inside auto layout */

    flex: none;
}
.botmid img{
    width: 20px;
    height: 20px;
}
.botmid{
    display: flex;
    gap: 20px;
    margin-top: 10px;
    margin-left: 10px;
}
.botrightinfop{
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 16px;
    margin-bottom: 0px;
    /* Text Grey */

    color: #858484;


    /* Inside auto layout */

    flex: none;
    order: 0;
}
.bottitle{
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 22px;
    margin-bottom: 0px;
    /* Black */

    color: #353E40;
}
.botrighta{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 8px;

    width: 85px;
    height: 115px;
   

    /* Inside auto layout */

    flex: none;
}
.botinfoleft p{
    font-family: 'Nunito';
font-style: normal;
font-weight: 500;
font-size: 12px;
line-height: 16px;

margin-bottom: 0px;

/* Light Grey */

color: #B5B5B5;


/* Inside auto layout */

flex: none;
}
.botinforight{
    display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;
gap: 54px;

width: 576px;
height: 115px;


/* Inside auto layout */

flex: none;
order: 1;
flex-grow: 0;
}
.botinfoleft{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;

    width: 412px;
    height: 115px;


    /* Inside auto layout */

    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 1;
}
.botinfo{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;

    width: 996px;
    height: 115px;


    /* Inside auto layout */

    flex: none;
    order: 1;
    flex-grow: 0;
}
.botline{

    width: 741px; 
    height: 0px;

    /* Dark divider */

    border: 1px solid #99AEC8;

    /* Inside auto layout */

    flex: none;

}
.botlogo p{
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
    flex: none;
    color: #353E40;
}
.botlogo{

    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;

    width: 214px;
    height: 47px;
}
.btitle{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 40px;

    width: 995px;
    height: 47px;
 
}
.bott{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 54px;

    /* position: absolute; */
    width: 1200.01px;
    height: 282px;
    left: 120px;
    bottom: 0px;
   
    margin: 150px auto;
}
@media only screen and (max-width:750px) {
    .bott{
        width: 100%;
        height: 403px;
        display: flex;
        flex-direction: column;
        align-items: flex-end;
        padding: 0px;
        gap: 20px;
    }
    .botline
    {
        width: 147px;
    height: 0px;

    /* Dark divider */

    border: 1px solid #99AEC8;
    transform: rotate(0.29deg);
    }
    .botinfo{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: flex-start;
        padding: 0px;
        gap: 20px;
        padding-left: 35px;
        width: 100%;
        height: 315px;


        /* Inside auto layout */

        flex: none;
        order: 1;
        align-self: stretch;
        flex-grow: 0;
        flex-wrap: wrap;
    }
    .btitle{
        display: flex;
        /* flex-direction: column;
        align-items: flex-end; */
        padding: 0px;
        gap: 16px;

        width: 335px;
        height: 54px;
        margin: 0px auto;
    }
    .finline{
        width: 335px;
    }
    .botinforight{
        width: 335px;
    }
     .botemail{
        gap: 10px;
        width: 100%;
     }
     .botrightb{
        width: 65px;
     }
    .botfin{
        width: 100%;
    }
}
</style>