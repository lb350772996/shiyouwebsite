<template>
    <div class="cust">
        <div class="custtitle">
             <p>我们的客户</p>
             <div class="custline"></div>
        </div>
        <div class="custlist">
            <img src="../assets/image 14.png" alt="">
            <img src="../assets/image 15.png" alt="">
            <img src="../assets/image 16.png" alt="">
            <img src="../assets/image 17.png" alt="">
        </div>
        <div class="custlist_m">
            <img src="../assets/m_image 14.png" alt="">
            <img src="../assets/image 15.png" alt="">
            <img src="../assets/image 16.png" alt="">
            <img src="../assets/image 17.png" alt="">
        </div>
    </div>
</template>
<script>
export default {
  name: 'CustOmer'
}
</script>
<style>
.custlist{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0px;
    gap: 102px;

    width: 1044px;
    height: 198px;
    /* background-color: blueviolet; */
}
.custline{
    width: 200px;
    height: 0px;

    /* Dark divider */

    border: 1px solid #99AEC8;

    /* Inside auto layout */

    flex: none;
    order: 1;
    flex-grow: 0;
}
.custtitle p{
    width: 247px;
    height: 48px;

    font-family: 'Nunito';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 55px;
    /* Black */
    color: #353E40;
    margin-bottom: 0px;
    margin-top: 0px;
}
.custtitle{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 24px;

    width: 1044px;
    height: 72px;
}
.cust{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 40px;

    /* position: absolute; */
    width: 1044px;
    height: 310px;
    /* background-color: aqua; */
    margin: 150px auto;
}
.custlist_m{
    display: none;
}
@media only screen and (max-width:750px) {
    .cust{
        margin-top: 150px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 0px;
        gap: 40px;

        width: 100%;
        height: 957px;
    }
    .custtitle{
        width: 335px;
    }
    .custlist{
        display: none;
    }
    
    .custlist{
        flex-wrap: wrap;
        width: 335px;
        height: 650px;
        gap:16px;
    }
    .custlist_m{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        padding: 0px;
        gap: 100px;
      
    }
    .custlist_m img{
        margin: 0px auto;
        width: 149px;
        height: 182px;
    }
}
</style>