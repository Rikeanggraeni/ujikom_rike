<template>
  <div class="container mt-4">
    <h1 class="text-center mb-4">Ekstrakurikuler Sekolah</h1>

    <!-- Daftar Ekstrakurikuler -->
    <section class="row">
      <!-- Ekstrakurikuler 1 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/basket.jpg" alt="Basketball" class="card-img-top"
            style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">Basketball</h5>
            <p class="card-text">Basketball adalah kegiatan ekstrakurikuler yang bertujuan untuk mengembangkan
              keterampilan fisik, kerjasama tim, dan sportivitas. Kegiatan ini diadakan setiap Senin dan Rabu sore.</p>
          </div>
        </div>
      </div>

      <!-- Ekstrakurikuler 2 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/volly.jpg" alt="volly" class="card-img-top" style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">Volly</h5>
            <p class="card-text">Bola voli merupakan permainan beregu yang bertujuan untuk memukul bola ke arah bidang
              lapangan lawan untuk mendapatkan poin.</p>
          </div>
        </div>
      </div>

      <!-- Ekstrakurikuler 3 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/assets/img/perisai diri.jpg" alt="Klub Sains" class="card-img-top"
            style="height: 200px; object-fit: cover" />
          <div class="card-body">
            <h5 class="card-title">Klub Sains</h5>
            <p class="card-text">Klub Sains bertujuan untuk menumbuhkan minat siswa dalam bidang ilmu pengetahuan alam.
              Siswa dapat melakukan eksperimen dan penelitian ilmiah.</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Ekstrakurikuler",
};
</script>

<style scoped>
/* Styling tambahan untuk halaman ekstrakurikuler */
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
