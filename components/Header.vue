<template>
    <div class="p-3 head d-flex justify-content-between">
        <div class="d-flex align-items-center">
            <img src="/assets/logo-smkn4.png" alt="" srcset="" style="width: 60px;">
            <p class="fs-3 p-3">SMKN 4 TASIKMALAYA</p>
        </div>
        <div class="info">
            <span class=""><p class="fs-4">Lokasi</p></span>Sukamenak,Purbaratu,Tasikmalaya
        </div>
    </div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary sticky-top border border-black">
  <div class="container-fluid">
    <div class="collapse navbar-collapse nav justify-content-center " id="navbarNav">
      <ul class="navbar-nav ">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Profile
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/profile/vm">Visi Misi</a></li>
            <li><a class="dropdown-item" href="/profile/sejarah">Sejarah</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="/profile/dp">Data pokok</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Estrakurikuler
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/eskul/ol">Olahraga</a></li>
            <li><a class="dropdown-item" href="/eskul/no">Non Olahraga</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/gallery">gallery</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

</template>
<style>
@media (max-width : 700px) {
  .info{
    display: none;
  }
}

</style>