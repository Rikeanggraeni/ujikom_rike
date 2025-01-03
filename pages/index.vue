<template>
  <div>
    <h1 class="text-center mb-4">Selamat Datang di Website Sekolah Kami!</h1>

    <!-- Gambar Sekolah -->
    <div class="row">
      <div class="col-md-12 text-center">
        <img
          src="/assets/img/skul.jpg"
          alt="Gambar Sekolah"
          class="img-fluid"
          style="
            width: 100%;
            max-height: 600px;
            object-fit: cover;
            align-items: center;
          "
        />
      </div>
    </div>

    <!-- Sambutan Kepala Sekolah -->
    <section class="mt-5">
      <h2 class="text-center">Sambutan Kepala Sekolah</h2>
      <div class="row justify-content-center mt-4">
        <div class="col-md-4 text-center">
          <!-- Foto Kepala Sekolah -->
          <img
            src="/assets/img/kepsek.png"
            alt="Foto Kepala Sekolah"
            class="img-fluid rounded-circle"
            style="width: 300px; height: 300px; object-fit: cover"
          />
        </div>
        <div class="col-md-6">
          <!-- Teks Sambutan -->
          <p>
            <strong>Selamat datang di website resmi sekolah kami!</strong><br />
            Assalamualaikum Warahmatullahi Wabarakatuh Selamat datang di SMKN 4
            Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah
            SWT, semoga kita semua ada dalam lindungan-Nya. Dan atas
            perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4
            Tasikmalaya ini. Kami berharap dengan adanya website di SMK Negeri 4
            Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang
            sekolah kami sehingga dapat mempererat tali silaturrahmi antara
            sekolah dengan masyarakat demi kemajuan kita bersama. Tiada gading
            yang tak retak, website kami ini masih dalam proses pengembangan,
            masih banyak kekurangan yang harus kami perbaiki. Kritik dan
            sarannya yang membangun sangat kami harapkan untuk pengembangan ke
            depan. Di sini, kami tidak hanya mengajarkan ilmu pengetahuan tetapi
            juga membentuk karakter siswa agar siap menghadapi tantangan masa
            depan. Kami berharap website ini dapat memberikan informasi yang
            bermanfaat dan memberi gambaran yang jelas tentang segala aktivitas
            di sekolah.
            <br /><br />
            Terima kasih atas kunjungan Anda. Semoga sekolah kami selalu menjadi
            tempat yang penuh inspirasi bagi anak-anak bangsa.
            <br /><br />
            <em>Hormat kami,</em><br />
            <strong>SMKN 4 TASIKMALAYA</strong><br />
            <strong>Kurniawan, S.Pd, M.Pd.</strong>
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
/* Tambahkan style untuk halaman utama */
h1 {
  color: #0056b3;
  font-weight: bold;
}

section {
  padding: 30px 0;
}

img {
  border-radius: 10px;
}

p {
  font-size: 16px;
  line-height: 1.6;
}

strong {
  color: #0056b3;
}

.text-center {
  text-align: center;
}
</style>
