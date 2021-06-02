<template>
    <div class="col main ">
        <div class="row  topsection ">
          <div class="col content">
            <h4 class="m-0">Dashboard</h4>
            <p class="m-0 p-0">Lorem ipsum dolor sit ipsum.</p>
          </div>
          <div class="col-3 left">
            <div class="row left-box-section">
              <i class="fa fa-calendar-o" aria-hidden="true"></i>
              <div class="pl-3">
                <h6 class="p-0 m-0">Filter Period</h6>
                <p class="p-0 m-0">................</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-2">
          <div class="col boxSection">
            <div class="row threeBoxSection ">
              <div class="col left-box"></div>
              <div class="col middle-box"></div>
              <div class="col right-box"></div>
            </div>
            <div class="row twoBoxSection">
              <div class="col tableSection"></div>
              <div class="col chartSection"></div>
            </div>
          </div>
        </div>
    </div>
</template>
<script>

</script>
<style scoped>
.main{
  height: 100vh;
  /* background-color: #f8f3f7; */
  /* padding: ; */
}
.topsection {
  margin-top: 40px;
  height: 80px;
}
.left-box-section{
  /* color: #c4837d; */
  background-color: #f8e7df;
  width: 260px;
  height: 58px;
  padding: 7px 23px  ;
  border-radius: 5px;
}
.left{
  /* padding-left: 45px; */
  height: 75px;
}
.content{
  height: 75px;
  padding: 0;
}
.content h4{
  font-weight: 700;
  font-size:28px ;
}
.content p{
  color: #797878;

}
.fa-calendar-o{
  font-size: 30px;
  color: #c4837d;
  padding-top: 8px;
}

.threeBoxSection{
    column-gap: 25px;
    height: 150px;
}
.left-box{
    background-color: #fff ;
    border-radius: 10px;
    box-shadow:0 1px 2px #8d8c8c44;
}
.middle-box{
    background-color: #fff ;
    border-radius: 10px;
    box-shadow:0 1px 2px #8d8c8c44;

}
.right-box{
    background-color: #fff ;
    border-radius: 10px;
    box-shadow:0 1px 2px #8d8c8c44;
}
.twoBoxSection{
    column-gap: 25px;
    height: 350px;
    margin-top: 25px;
}
.chartSection{
    background-color: #fff ;
    border-radius: 2px;
    box-shadow:0 1px 2px #8d8c8c44;
}
.tableSection{
    background-color: #fff ;
    border-radius: 2px;
    box-shadow:0 1px 2px #8d8c8c44;
}
</style>