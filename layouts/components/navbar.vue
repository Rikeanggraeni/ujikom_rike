<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <!-- Logo -->
      <a class="navbar-brand" href="/">
        <img src="assets/img/logo.png" alt="Logo Sekolah" width="60" height="60" class="d-inline-block align-text-top" />
      </a>

      <!-- Toggle Button untuk Mobile -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Menu Navigasi -->
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <NuxtLink class="nav-link active" to="/">Beranda</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/profil">Profil Sekolah</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/ekstrakurikuler">Ekstrakurikuler</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/jurusan">jurusan</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/Galeri">Galeri</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
/* Kustomisasi warna atau style navbar jika diperlukan */
.navbar {
  border-bottom: 2px solid #ccc; /* Contoh border di bawah navbar */
}

.navbar-brand img {
  border-radius: 50%; /* Membuat logo menjadi bulat */
}
</style>
