<template>
  <div class="container mt-4">
    <h1 class="text-center mb-4">Jurusan Sekolah</h1>

    <!-- Daftar Jurusan -->
    <section class="row">
      <!-- Jurusan 1: PPLG -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/RPL.jpeg" alt="PPLG" class="card-img-top" style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">JURUSAN PPLG</h5>
            <p class="card-text">
              Jurusan PPLG atau Pengembangan Perangkat Lunak dan Gim adalah jurusan yang mempelajari tentang
              perkembangan perangkat lunak meliputi pembuatan, manajemen organisasi pengembangan perangkat lunak,
              pemeliharaan, dan manajemen kualitas.
            </p>
          </div>
        </div>
      </div>

      <!-- Jurusan 2: TJKT -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/tjktt.jpeg" alt="TJKT" class="card-img-top" style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">JURUSAN TJKT</h5>
            <p class="card-text">
              Teknik Jaringan Komputer dan Telekomunikasi (TJKT) merupakan program keahlian yang membekali peserta didik
              dengan keterampilan, pengetahuan, dan sikap agar kompeten dalam merakit, menginstall program, merawat dan
              memperbaiki komputer serta jaringannya.
            </p>
          </div>
        </div>
      </div>

      <!-- Jurusan 3: TBSM -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/tsm.jpeg" alt="TBSM" class="card-img-top" style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">JURUSAN TBSM</h5>
            <p class="card-text">
              Teknik Bisnis Sepeda Motor adalah kompetensi keahlian pada Bidang Studi Keahlian Teknologi dan Rekayasa
              Program Studi Keahlian Teknik Otomotif yang menekankan pada keterampilan pelayanan jasa mekanik kendaraan
              sepeda motor roda dua.
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/dkv.png" alt="TBSM" class="card-img-top" style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">JURUSAN DKV</h5>
            <p class="card-text">
              urusan Desain Komunikasi Visual (DKV) adalah studi yang mempelajari ilmu tentang penyampaian pesan dengan menggunakan elemen desain grafis,
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/TOI.jpeg" alt="TBSM" class="card-img-top" style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">JURUSAN TOI</h5>
            <p class="card-text">
              Teknik otomasi industri (TOI) adalah suatu jurusan teknik yang menerapkan sistem pengajaran yang mengarah ke bidang perakitan sistem-sistem
            </p>
          </div>
        </div>
      </div>

    </section>
  </div>
</template>

<script>
export default {
  name: "Jurusan",
};
</script>

<style scoped>
/* Styling tambahan untuk halaman jurusan */
.card {
  border-radius: 10px;
  border: 1px solid #ddd;
}

.card-img-top {
  height: 200px;
  object-fit: cover;
}

h2 {
  color: #0056b3;
  font-weight: bold;
  margin-bottom: 20px;
}

.table {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.table th,
.table td {
  text-align: center;
  vertical-align: middle;
}

.table-bordered {
  border: 1px solid #ddd;
}

.table th {
  background-color: #f8f9fa;
  color: #0056b3;
}

.card-body {
  padding: 20px;
}
</style>
