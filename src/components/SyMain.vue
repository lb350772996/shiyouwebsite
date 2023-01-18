<template>
  <div class="Vector2">
    <TopHeader />
    <OursList />
    <WhyMe />
    <WhoMi />
    <WhoMu />
    <DataSta />
    <CustOmer />
     <SyBott />
  </div>
</template>

<script>
import OursList from './OursList.vue';
import TopHeader from './TopHeader.vue';
import WhoMi from './WhoMi.vue';
import WhyMe from './WhyMe.vue';
import WhoMu from './WhoMu.vue'
import DataSta from './DataSta.vue'
import CustOmer from './CustOmer.vue';
import SyBott from './SyBott.vue'
export default {
    name: "SyMain",
    props: {
        msg: String
    },
    components: { TopHeader, OursList, WhyMe, WhoMi, WhoMu, DataSta, CustOmer ,SyBott}
    // components: { TopHeader, OursList, WhyMe, WhoMi, WhoMu,DataSta, CustOmer}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Vector2 {
  position: absolute;
  width: 100%;
  height: 100%;
  overflow-y: auto;
  overflow-x: hidden;
  left: 0px;
  top: 0px;
  background: linear-gradient(109.5deg, #F0F5F8 29.9%, #DCF3FF 77.69%);

}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
