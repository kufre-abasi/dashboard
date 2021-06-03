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
                <p class="pt-0 date">10 jan 2021 - 31 jan 2021</p>
              </div>
              <i class="fa fa-caret-down" aria-hidden="true"></i>
            </div>
          </div>
        </div>
        <div class="row mt-2 ">
          <div class="col boxSection">
            <div class="row threeBoxSection ">

              <div class="col left-box">
                <div class="row">
                  <a class="nav-link round-area-left" href="#"><i class="fa fa-file-text" aria-hidden="true"></i><span class="sr-only">(current)</span></a>
                  <div class="pl-3 pt-2">
                     <h6 class="py-0 my-0">Total Orders</h6>
                     <p class="py-0 my-0 txt"><span class="amount">300</span> 10% up (30 days)</p>
                   </div>
                </div>
              </div>

              <div class="col middle-box">
                <div class="row">
                  <a class="nav-link round-area-middle" href="#"><i class="fa fa-user" aria-hidden="true"></i><span class="sr-only">(current)</span></a>
                  <div class="pl-3 pt-2">
                     <h6 class="py-0 my-0">Total Customers</h6>
                     <p class="py-0 my-0 txt"><span class="amount">150</span> 4% up (30 days)</p>
                   </div>
                </div>
              </div>
              <div class="col right-box">
                <div class="row">
                  <a class="nav-link round-area-right" href="#"><i class="fa fa-usd" aria-hidden="true"></i><span class="sr-only">(current)</span></a>
                  <div class="pl-3 pt-2">
                     <h6 class="py-0 my-0">Total Revenue</h6>
                     <p class="py-0 my-0 txt"><span class="amount">N 450K</span> 20% up (30 days)</p>
                   </div>
                </div>
              </div>
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
    padding: 40px 0px;
    padding-left: 43px  !important;
}
.middle-box{
    background-color: #fff ;
    border-radius: 10px;
    box-shadow:0 1px 2px #8d8c8c44;
    padding: 40px 0px;
    padding-left: 43px  !important;
}
.right-box{
    background-color: #fff ;
    border-radius: 10px;
    box-shadow:0 1px 2px #8d8c8c44;
    padding: 40px 0px;
    padding-left: 43px  !important;
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
.boxSection{
  padding-left:18px ;
}
.date{
  font-size: small;
}
.fa-caret-down{
  padding: 13px 0px;
  padding-left: 10px  !important;
}
.round-area-left{
  height: 70px;
  width: 70px;
  background-color: #f8e7df;
  border-radius: 40px;
  padding: 0px 16px;
  font-size: 45px;
  color: #c4837d;

}
.round-area-left:hover{
  background-color:#c4837d;
  color:#f8e7df ;
}
.amount{
  font-weight: 700;
  font-size: 25px;
  color: #000;
}
.txt{
    color: #797878;
    font-size: 14px;

}
.round-area-middle{
  height: 70px;
  width: 70px;
  background-color: #f8e7df;
  border-radius: 40px;
  padding: 0px 19px;
  font-size: 46px;
  color: #c4837d;
}
.round-area-middle:hover{
  background-color:#c4837d;
  color:#f8e7df ;
}
.round-area-right{
  height: 70px;
  width: 70px;
  background-color: #f8e7df;
  border-radius: 40px;
  padding: 0px 22px;
  font-size: 46px;
  color: #c4837d;
}
.round-area-right:hover{
  background-color:#c4837d;
  color:#f8e7df ;
}
</style>