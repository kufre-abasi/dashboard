<template>
    <div class="row main " id="sidebar" >
        <div class="col  pl-0" >
            <!-- <div class=""> -->
            <nav class="navbar navbar-dark  row" id="contant">
                 <a class="navbar-brand m-0" href="#"><h4><span class="hd">CHOP</span>CHOP</h4></a>
                
                <button  onclick="adjust" class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fa fa-bars " aria-hidden="true"></i>
                </button>
            </nav>
            <div class="row navbar-nav  ">
                <div class="col nav-item active p-0">
                    <a class="nav-link " href="#"><span class="ft1"><i class="fa fa-tachometer" aria-hidden="true"></i></span> Dashboard <span class="sr-only">(current)</span></a>
                    <a class="nav-link " href="#"><span class="ft2"><i class="fa fa-list-alt" aria-hidden="true"></i></span> Order <span class="sr-only">(current)</span></a>
                    <a class="nav-link " href="#"><span class="ft3"><i class="fa fa-calendar-minus-o" aria-hidden="true"></i></span> Menus <span class="sr-only">(current)</span></a>
                    <a class="nav-link " href="#"><span class="ft4"><i class="fa fa-users" aria-hidden="true"></i></span> Customers <span class="sr-only">(current)</span></a>
                    <a class="nav-link " href="#"><span class="ft5 pl-1"><i class="fa fa-usd" aria-hidden="true"></i></span> Payments <span class="sr-only">(current)</span></a>
                    <a class="nav-link " href="#"><span class="ft6 pl-1"><i class="fa fa-cog" aria-hidden="true"></i></span> Settings <span class="sr-only">(current)</span></a>
                </div>
            </div>
        </div>
    </div>
    <!--           <div class="sidebar " id="sidebar">

          </div>
          <div class="main-content" id="contant">
            <button onclick="adjust" class="btn btn-white"><i class="fa fa-bars bg-info" aria-hidden="true"></i></button>

          </div>
 -->
</template>

<script>

// function adjust(){
//     let side = document.querySelector(".sidebar");
//     let main = document.querySelector("#content");
//     if(side.clientWidth.style === "150px"){
//         side.clientWidth.style = "50px";
//         main.style.marginleft = "50px";
//     }
//     else{
//         side.style.width = "150px";
//         main.style.marginleft = "150px";
//     }
// }
</script>

<style scoped>
.main{
  /* border-right: solid 2px rgba(128, 128, 128, 0.418); */
    height: 100vh;
    /* box-shadow:0 5px 5px #797878; */
    width: auto;
    height: 100vh;
    background: #fff;
    box-shadow: 6px 0 18px rgb(0 0 0 / 7%);

}
.navbar-dark{
    padding-top: 30px;
}
.navbar-toggler {
    border-color: rgba(255, 255, 255, 0.1) 2px;
    /* margin-right: 5px !important; */

}
.nav-link{
    /* font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; */
    font-size: 15px;
    /* font-weight: bold; */
    color: #797878;
    height: 65px;
    padding-left: 30px;
}
.nav-link:hover{
    background-color: #f8e7df;
    color: #c4837d;
}
.hd{
    color: #c4837d;
    padding-left: 35px;
    /* padding-right: 0; */
}
.navbar a{
    font-weight: 500;
    padding-top: 10px  !important;
}
h4{
    color: #000;
}
.navbar-nav{
    margin-top: 30px  !important;
    padding-left: 30px;
}
.ft1{
    font-size: 20px;
    padding-right: 36px;
}
.ft2{
    font-size: 20px;
    padding-right: 36px;
}
.ft3{
    font-size: 20px;
    padding-right: 36px;

}
.ft4{
    font-size: 20px;
    padding-right: 36px;
}
.ft5{
    font-size: 20px;
    padding-right: 36px;
}
.ft6{
    font-size: 20px;
    padding-right: 36px;
}
.fa-bars {
    font-size: 30px;
    color: black;
}
</style>