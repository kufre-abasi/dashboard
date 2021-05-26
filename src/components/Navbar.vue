<template>
<div class="col pl-0">
    <nav class="navbar navbar-expand-lg  ">
        <form class="form-inline ">
            <input class="form-control mr-sm-0 " type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline my-2 my-sm-0 search" type="submit"><i class="fa fa-search" aria-hidden="true"></i></button>
        </form>
        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
        <!-- <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button> -->
        <div class="collapse navbar-collapse " id="navbarNav">
            <ul class="navbar-nav ">
            <li class="nav-item active">
                <a class="nav-link" href="#">About <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item active">
                <a class="nav-link" href="#">Tools <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item active">
                <a class="nav-link" href="#">Help <span class="sr-only">(current)</span></a>
            </li>
            </ul>

        </div>
        <div class="col">
            <div class="row">
                <a class="nav-link" href="#"><i class="fa fa-bell" aria-hidden="true"></i> <span class="sr-only">(current)</span></a>
                <a class="nav-link" href="#"><i class="fas fa-facebook-messenger    "></i> <span class="sr-only">(current)</span></a>
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
    width: 280px;
    /* padding: 20px; */
    color: #495057;
    background-color: #fff;
}
.navbar-collapse{
    padding-left: 110px;
}
.nav-link{
    color: black;
    font-weight: 500;
}
.nav-link:hover{
    color: #c4837d;
    font-weight: 700;
}
</style>