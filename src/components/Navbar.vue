<template>
<div class="col pl-0 ml-0">
    <nav class="navbar navbar-expand-lg  pl-0">
        <form class="form-inline col-5   ">
            <input class="form-control mr-sm-0 " type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline my-2 my-sm-0 search" type="submit"><i class="fa fa-search" aria-hidden="true"></i></button>
        </form>
        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
        <!-- <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button> -->
        <div class="collapse navbar-collapse col-3 " id="navbarNav">
            <ul class="navbar-nav ">
            <li class="nav-item active">
                <a class="nav-link navitem" href="#">About <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item active px-3">
                <a class="nav-link navitem" href="#">Tools <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item active">
                <a class="nav-link navitem" href="#">Help <span class="sr-only">(current)</span></a>
            </li>
            </ul>

        </div>
        <div class="col-2">
            <div class="row icons"> 
                <a class="nav-link " href="#"><i class="fa fa-bell" aria-hidden="true"></i> <span class="sr-only">(current)</span></a>
                <a class="nav-link " href="#"><i class="fa fa-comment" aria-hidden="true"></i> <span class="sr-only">(current)</span></a>
            </div>
        </div>
        <div class="col">
            <div class="row  user p-0">
                    <h6 class="col-9 username m-0 pt-2">Hello,Mike</h6>
                    <div class="col-3  userimg"></div>
            </div>
        </div>
</nav>
    </div>
</template>

<script>
</script>
<style scoped>
.navbar{
    padding: 18px ;
    background-color: #fff ;
}
.search{
    border: none ;
    color: #495057;
    position: relative;
    left: -40px;
}
.form-control{
    border-radius:0 ;
    width: 330px;
    /* padding: 20px; */
    color: #495057;
    background-color: #fff;
}
.navbar-collapse{
    padding-left: 80px;
    padding-right: 0px;
}
.navitem{
    font-weight: 500;
    color: black;

}
.navitem:hover{
    /* font-weight: 700; */
    color: #c4837d;
}
.fa-comment{
    font-weight: 500;
    color: #c4837d;
}
.fa-comment:hover{
    font-size: large;
    /* color: black; */
}
.fa-bell{
    font-weight: 500;
    color: #c4837d;
}
.fa-bell:hover{
    font-size: large;
    /* color: black; */
}
.userimg{
    height:40px ;
    width: 40px;
    border-radius: 50px;
    background-image: url(../assets/image/user.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}
.user{
    border-radius:0 50px  50px  0  ;
    background-color: #c4837d;
    color: #fff;
}
.icons{
    padding-left: 53px;
}
</style>