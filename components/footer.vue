<template>
  <footer class="bg-dark text-light text-center py-4">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <h5>Kontak</h5>
          <ul class="list-unstyled">
            <li><a href="tel:+6281234567890" class="text-light">+(62)265312059</a></li>
            <li><a href="mailto:sekolahku@example.com" class="text-light">info@smkn4tsm.sch.id</a></li>
          </ul>
        </div>
        <div class="col-md-4">
          <h5>Alamat</h5>
          <p class="text-light">Jalan Depok RT 02 RW 05</p>
        </div>
        <div class="col-md-4">
          <h5>Ikuti Kami</h5>
          <div>
            <a href=" https://www.facebook.com/4smkn" class="text-light mx-2" target="_blank"><i
                class="fab fa-facebook"></i> Facebook</a>
            <a href="https://www.instagram.com/smkn4tsmofficial?igsh=djRxa2xlMWY1a3Zo" class="text-light mx-2"
              target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
footer {
  background-color: #343a40;
  color: white;
}

footer a {
  text-decoration: none;
}

footer a:hover {
  text-decoration: underline;
}

footer .fab {
  margin-right: 10px;
}
</style>
