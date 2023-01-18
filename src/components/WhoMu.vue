<template>
    <div class="whomib">
        <div class="whomitop"><p>我们的领导</p> <div class="wholine"></div></div>
        <div class="wholeader">
            <div >
                <img src="../assets/image 10.png" alt="">
                <div class="ltop"><p class="leaderp1">宋杰</p>
                    <p class="leaderp2">董事长</p>
                </div>
                <p class="leaderp3">领导力不是一个头衔或称号。它关乎影响、影响和灵感。</p>
            </div>
            <div >
                <img src="../assets/image 11.png" alt="">
                <div class="ltop"><p class="leaderp1">贺晓卉</p>
                    <p class="leaderp2">监事</p>
                </div>
                <p class="leaderp3">影响力包括获得结果，影响力是关于传播你对工作的热情。</p>
            </div>
            <div >
                <img src="../assets/image 12.png" alt="">
                <div class="ltop"><p class="leaderp1">贺晓卉</p>
                    <p class="leaderp2">监事</p>
                </div>
                <p class="leaderp3">在我们公司开发网站和设计。具有丰富的市场营销和人力资源经验</p>
            </div>
            
        </div>
    </div>
</template>
<script>
export default {
  name: 'WhoMu'
}
</script>
<style>
.ltop{
    display: flex;
    gap: 20px;
    height: 50px;
}
.leaderp3{
    width: 263px;
    height: 38px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 19px;

    /* Text Grey */

    color: #858484;


    /* Inside auto layout */

    flex: none;
    order: 1;
    flex-grow: 0;
}
.leaderp2{
    width: 42px;
    height: 19px;
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 19px;
    margin-top: 20px;
    /* identical to box height */

    text-decoration-line: underline;

    /* Active */

    color: #007BFF;


    /* Inside auto layout */

    flex: none;
    order: 1;
    flex-grow: 0;
}
.leaderp1{
    /* width: 48px; */
    height: 33px;
    margin-top: 12px;
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 33px;
    /* identical to box height */


    /* Black */

    color: #353E40;


/* Inside auto layout */

flex: none;
order: 0;
flex-grow: 0;
}
.wholeader{
    display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 116px;
margin-left: 36px;
width: 1044px;
height: 421px;


/* Inside auto layout */

flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
/* background-color: aqua; */
}
.wholine{
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
.whomitop p{
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
.whomitop{
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
.whomib{
    display: flex;
    /* background-color: aqua; */
    /* position: absolute; */
    width: 1200px;
    height: 698px;
    margin: 0px auto;
    background: #F9F9F9;
    /* border-radius: 20px 129px 20px 20px; */
    flex-flow: wrap;
    margin-bottom: 200px;
}
@media only screen and (max-width:750px) {
    .wholeader{
        
        width: 335px;
        height: 1046px;
        flex-wrap: wrap;
        gap: 20px;
        margin-bottom: 100px;
    
    }
   
    .whomib{
        width: 100%;
       
        height: 1376px;
    }
}

</style>