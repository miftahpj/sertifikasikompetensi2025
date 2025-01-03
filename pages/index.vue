<script setup>
useHead({
  title: 'Beranda SMKN 4 tasikmalaya',
});

</script>
<template>
  <div class="welcome">
    <div class="position-absolute top-50 start-50 translate-middle">
      <h1 class="text-md-center fw-bold text-white">SELAMAT DATANG DI WEBSITE SMKN 4 TASIKMALAYA</h1>
    </div>
  </div>

  <div class="container">
    <div class="row p-3">
      <div class="col-lg-4">
        <img src="/assets/kepsek.png" alt="" srcset="" style="height: 400px; width: 400px;">
        <p class="fs-4 text-center">Kurniawan s.pd m.pd</p>
        <p class="text-center">Kepala Sekolah SMKN 4 Tasikmalaya</p>
      </div>
      <div class="col-lg-8">
        <h1 class="text-center">Sambutan </h1>
        <p class="fs-5 text-md-center ">Selamat datang di website smkn 4 semoga anda </p>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row p-4">
      <div class="col-lg-8">
        <div id="carouselExample" class="carousel slide">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="/assets/gallery/g2.jpg" class="d-block w-100 rounded-4" alt="...">
            </div>
            <div class="carousel-item">
              <img src="/assets/gallery/g3.jpg" class="d-block w-100 rounded-4" alt="...">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
      <div class="col-lg-4 p-3">
        <h3 class="">BERITA</h3>
        <p class="placeholder-glow ">
          <span class="placeholder col-12 " style="width: 25%;"></span>
        </p>
        <div>
          <h4>PPDB</h4>
          <P>PPDB SMKN 4 Tasikmalaya dimulai pada juni hingga juli</P>
          <a class="btn btn-primary" data-bs-toggle="offcanvas" href="#offcanvasExample" role="button"
            aria-controls="offcanvasExample">
            Tekan untuk info lebih lanjut
          </a>
          <div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasExample"
            aria-labelledby="offcanvasExampleLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasExampleLabel">PPDB</h5>
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <div>
                PPDB SMKN 4 TASIKMALAYA dimulai pada juni hingga juli dengan menyediakan 5 jurusan yaitu tjkt dengan
                kota 140 siswa,pplg dengan kota 140 siswa,tbsm dengan kota 140 siswa,toi dengan kota 140 siswa,dkv
                dengan kota 140 siswa
              </div>
            </div>
          </div>
        </div>
        <h4 class="pt-2">yudy bareto</h4>
        <P>datang nya yudi bareto untuk melakukan kegiatan edufest</P>
        <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#staticBackdrop"
          aria-controls="staticBackdrop">
          Tekan untuk info lebih lanjut
        </button>

        <div class="offcanvas offcanvas-start" data-bs-backdrop="static" tabindex="-1" id="staticBackdrop"
          aria-labelledby="staticBackdropLabel">
          <div class="offcanvas-header">
            <h5 class="offcanvas-title" id="staticBackdropLabel">Offcanvas</h5>
            <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
          </div>
          <div class="offcanvas-body">
            <div>
              I will not close if you click outside of me.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="">
    <h1 class="text-center bg-secondary">data static</h1>
  </div>

  <div class="container text-center">
    <div class="row p-5">
      <div class="col-sm-6 mb-3 mb-sm-0">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Jumlah Guru 120</h5>
          </div>
        </div>
      </div>
      <div class="col-sm-6">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Jumlah murid 1340</h5>
          </div>
        </div>
      </div>
    </div>

    <div>
      <h1 class="text-center">Baju Praktik Jurusan</h1>
      <div class="justify-content-center">
        <div class="row justify-content-center p-2 text-center">
            <div class="col-lg-4 p-1">
                <div class="card" style="width: 18rem;">
                    <img src="/assets/Jurusan/dkv.jpg" class="card-img-top " alt="...">
                        <div class="card-body">
                            <p class="card-text fs-4">DKV</p>
                        </div>
                </div>
            </div>
            <div class="col-lg-4 p-1">
                <div class="card" style="width: 18rem;">
                    <img src="/assets/Jurusan/pplg.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text fs-4">PPLG</p>
                        </div>
                </div>
            </div>
            <div class="col-lg-4 p-1">
                <div class="card" style="width: 18rem;">
                    <img src="/assets/Jurusan/tbsm.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text fs-4">TBSM</p>
                        </div>
                </div>
            </div>
            <div class="col-lg-4 p-1">
                <div class="card" style="width: 18rem;">
                    <img src="/assets/Jurusan/tjkt.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text fs-4">TJKT</p>
                        </div>
                </div>
            </div>
            <div class="col-lg-4 p-1">
                <div class="card" style="width: 18rem;">
                    <img src="/assets/Jurusan/toi.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text fs-4">TOI</p>
                        </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.welcome {
  background-image: url(/assets/home.JPG);

  width: 100%;
  height: 85vh;

  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

</style>