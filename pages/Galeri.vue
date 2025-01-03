<template>
  <div class="container-fluid">
    <!-- Judul Halaman Galeri -->
    <section class="gallery-header text-center py-5">
      <h2>Galeri Sekolah</h2>
      <p>Berikut adalah beberapa kegiatan dan acara yang telah berlangsung di SMK Negeri 4 Tasikmalaya.</p>
    </section>

    <!-- Galeri Foto -->
    <section class="gallery-section py-5">
      <div class="gallery-row">
        <!-- Gambar 1 -->
        <div class="gallery-card">
          <img src="assets/img/kunjungan.jpeg" alt="Gambar 1" class="img-fluid gallery-image" />
          <div class="overlay">
            <p class="overlay-text">Kunjungan Industri</p>
          </div>
        </div>

        <!-- Gambar 2 -->
        <div class="gallery-card">
          <img src="assets/img/poto.jpeg" alt="Gambar 2" class="img-fluid gallery-image" />
          <div class="overlay">
            <p class="overlay-text">Jobfair</p>
          </div>
        </div>

        <!-- Gambar 5 -->
        <div class="gallery-card">
          <img src="assets/img/MPLS.jpeg" alt="Gambar 3" class="img-fluid gallery-image" />
          <div class="overlay">
            <p class="overlay-text">Pembukaan MPLS</p>
          </div>
        </div>

        <!-- Gambar 6 -->
        <div class="gallery-card">
          <img src="assets/img/kemah.jpeg" alt="Gambar 4" class="img-fluid gallery-image" />
          <div class="overlay">
            <p class="overlay-text">Kemah</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "GaleriSekolahPage",
};
</script>

<style scoped>
.gallery-header {
  background-color: #007bff;
  color: white;
  padding: 20px 0;
  border-bottom: 2px solid #0056b3;
}

.gallery-header h2 {
  font-size: 22px;
  font-weight: bold;
}

.gallery-header p {
  font-size: 15px;
  margin-top: 10px;
}

.gallery-section {
  background-color: #f7f7f7;
}

.gallery-row {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.gallery-card {
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease-in-out;
  width: 15%;
  margin-bottom: 20px;
}

.gallery-card:hover {
  transform: scale(1.05);
}

.gallery-image {
  width: 100%;
  height: 300px;
  object-fit: cover;
  transition: opacity 0.3s ease-in-out;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.6);
  color: white;
  opacity: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: opacity 0.3s ease-in-out;
  text-align: center;
}

.overlay-text {
  font-size: 18px;
  font-weight: bold;
  padding: 10px;
}

.gallery-card:hover .overlay {
  opacity: 1;
}

h2 {
  text-emphasis: center;
}

h3 {
  color: #0056b3;
  font-size: 30px;
}

@media (max-width: 768px) {
  .gallery-card {
    width: 30%;
    /* Menyesuaikan ukuran gambar di layar kecil */
  }

  .gallery-image {
    height: 120px;
    /* Memperkecil gambar pada layar kecil */
  }

  .gallery-row {
    justify-content: center;
    /* Menyusun gambar dengan rapi pada layar kecil */
  }
}
</style>