<template>
  <div id="app "  class="row mx-0 ">
    <div class="col-2  left p-0">
        <LeftSection/>
    </div>

    <div class="col-10  right">
        <div class="row mx-0 ">
            <Navbar/>
        </div>
        <div class="row mx-0  bottom">
            <Bottomsection/>
        </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LeftSection from './components/LeftSection'
import Navbar from './components/Navbar'
import Bottomsection from './components/Bottomsection'
export default {
  name: 'App',
  components: {
    LeftSection,
    Navbar,
    Bottomsection,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  height: 100vh;
  padding: 20px  !important;
}
.left{
  height: 99vh;
}
.right{
  height: 99vh;
}
.bottom{
  background-color: #f8f3f7;
  padding: 20px;
}
</style>
