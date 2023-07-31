<!--
    use this to install AOS animation 
    npm i --save-dev @types/aos
-->

<template>
  <div id="body">
    <nav id="navbar" class="navbar navbar-expand-lg navbar-dark fixed-top" aria-label="Offcanvas navbar large">
        <div class="container">
            <a class="navbar-brand text-bold">Logo</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar2" aria-controls="offcanvasNavbar2">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasNavbar2" aria-labelledby="offcanvasNavbar2Label">
                <div class="offcanvas-header">
                    <h5 class="offcanvas-title" id="offcanvasNavbar2Label">@Delizioso.tgr</h5>
                    <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body">
                    <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="https://wa.me/6287877108198">Whatsapp</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="www.instagram.com/delizioso.tgr">Instagram</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
    <div class="my-5">
        <br>
        <div id="title" class="text-center mb-3 mt-4">
            <h1>@Delizioso.tgr</h1>
        </div>
        <div id="banner">
            <div class="mx-auto">
                <img id="banner1" src="./gambar/banner1.png">
            </div>
        </div>
    </div>
    <div id="highlights" class="text-center">
        <h1 class="mb-5 mt-2" style="font-weight: 650; font-size: 30px;">Highlights</h1>
        <div id="myCarousel" class="carousel slide mt-2" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner" data-aos="fade-up" data-aos-duration="1300">
                <div class="carousel-item active">
                    <div class="container">
                        <div class="carousel-caption">
                            <img id="gambarProduk" src="./gambar/delizioso1.png"/>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="container">
                        <div class="carousel-caption">
                            <img id="gambarProduk" src="./gambar/delizioso2.png"/>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="container">
                        <div class="carousel-caption">
                            <img id="gambarProduk" src="./gambar/delizioso3.png"/>
                        </div>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
            <div id="content"></div>
        </div>
    </div>
    <div id="product" class="my-5">
        <h1 style="font-weight: 650; font-size: 30px;" data-aos="fade-up" data-aos-duration="1000">Best Seller</h1>
        <div class="container">
            <div class="row">
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso5.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso1.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso2.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso3.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso5.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso1.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso2.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso3.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso5.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso1.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso2.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso3.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso4.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3 my-2" data-aos="fade-up" data-aos-duration="1300">
                    <div class="card">
                        <img class="card-img-top" src="./gambar/delizioso5.png">
                        <div class="card-body">
                            <h5 class="card-title">Rp 249.000</h5>
                            <h5>Mukena Tazbiya Kids Flower Red Rose</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="footer" class="pb-2 pt-4">
        <div class="container">
            <div class="row" style="font-weight: bold;">
                <div id="divsosmed" class="col-md-6 txt-md-end d-flex align-items-center">
                    <h3 style="font-weight: bolder;">DELIZIOSO.TGR</h3>
                </div>
                <div class="col-md-6 txt-md-end">
                    <div id="sosmed" class="text-end my-2">
                        <img src="./gambar/instagram.png" class="img-fluid mx-2">
                        <img src="./gambar/whatsapp2.png" class="img-fluid">
                    </div>
                    <div class="text-end my-3">
                        <p>Copyright &copy; 2022, All rights reserved.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
#body {
    background-color: #F7F5EB;
    font-family: 'Righteous', cursive;
}

/* BANNER */
#banner {
    width: 100%;
    height: auto;
}
#banner1 {
    width: 100%;
}
/* NAVBAR OFF CANVAS */
.bd-placeholder-img {
    font-size: 1.125rem;
    text-anchor: middle;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none;
}
@media (min-width: 768px) {
    .bd-placeholder-img-lg {
      font-size: 3.5rem;
    }
}
.b-example-divider {
    height: 3rem;
    background-color: rgba(0, 0, 0, .1);
    border: solid rgba(0, 0, 0, .15);
    border-width: 1px 0;
    box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
}
.b-example-vr {
    flex-shrink: 0;
    width: 1.5rem;
    height: 100vh;
}
.bi {
    vertical-align: -.125em;
    fill: currentColor;
}
.nav-scroller {
    position: relative;
    z-index: 2;
    height: 2.75rem;
    overflow-y: hidden;
}
.nav-scroller .nav {
    display: flex;
    flex-wrap: nowrap;
    padding-bottom: 1rem;
    margin-top: -1px;
    overflow-x: auto;
    text-align: center;
    white-space: nowrap;
    -webkit-overflow-scrolling: touch;
}
#navbar {
    background-color: #A0C3D2;
    font-weight: 400;
    font-size: 1.2rem;
}
.nav-link:hover {
    color: white;
    opacity: 1;
}
.dropdown-item:hover {
    color: #E46868;
    transition: 0.3s;
}

/* HEADER */
#title h1{
    font-weight: 600;
    color: #E46868;
}
#banner {
    background-color: #A6A6A6;
}

/* CAROUSEL */
.carousel-item {
    height: 30rem;
}
@media (max-width: 600px) {
    .carousel-item {
        height: 18rem;
    }
}
#gambarProduk {
    max-width: 100%;
    height: auto;
}
.carousel .carousel-indicators button {background-color: rgb(55, 53, 53);}
.carousel .carousel-indicators button.active {background-color: rgb(5, 5, 5);}
.carousel-control-prev-icon {
    filter: brightness(0.2);
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E") !important;
}
.carousel-control-next-icon {
    filter: brightness(0.2);
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E") !important;
}

/* HIGHLIGHTS */
#highlights h1 {
    color: #E46868;
    margin-bottom: 30px;
}

/* PRODUCT */
.card {
    border: none;
}
.card-body {
    background-color: #F7F5EB;
}
.card-title {
    color: #a84242;
}
#product h1 {
    color: #E46868;
    text-align: center;
    margin-bottom: 30px;
}
.card-img-top {
    transition: transform 1s;
    overflow: hidden;
}
.card-img-top:hover {
    transform: scale(1.3);
}

/* FOOTER */
#footer {
    background-color: #E4A9A9;
}
#sosmed img{
    width: 50px;
}
</style>
