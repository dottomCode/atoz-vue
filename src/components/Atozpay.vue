<template>
  <div>
     <section id="profile" class="profile pd-section">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6 col-md-7 order-md-1 order-2" data-aos="fade-up">
            <h1 class="pb-2">Atozpay untuk Semua</h1>
            <p>PT. Weyland Indonesia Perkasa (PT.WIP) adalah sebuah perusahaan anak Bangsa Indonesia yg
              profesional dan berpengalaman yang mendapatkan dukungan dari Weyland Tech Inc, sebuah
              perusahaan publik di AS yang membuat dan menyediakan aplikasi seluler untuk mendukung ribuan
              Perusahaan Kecil-Menengah.
            </p>
            <p> Para Profesional Indonesia yang tergabung dalam PT WIP menciptakan beberapa produk yang siap
              melayani masyarakat bernama atozpay, atozgo, atozpay agen dan atozpay createapp.</p>
            <p>
              Mau bayar tagihan bulanan, tapi jalanan macet? Enggak usah khawatir. Kamu tinggal buka
              aplikasi atozpay. Lalu pilih pembayaran tagihan, tagihan bulanan Telkom, dan masukkan nomor
              telepon milikmu.
            </p>
          </div>
          <div data-aos="zoom-in"
            class="col-lg-6 col-md-5 text-center order-md-2 order-1 mt-lg-0 pt-lg-0 mt-md-5 pt-md-5 pb-sm-3 pb-3">
            <div class="profile__img">
              <img class="img-fluid" src="images/homepage.webp" alt="model-img">
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="service pd-section">
      <div class="container">
        <h2 class="text-center mb-5">Layanan Kami</h2>
        <div class="row">
          <div class="col-lg-3 col-md-6 col py-lg-0 py-md-2 py-sm-2 py-2 p-lg-1 px-md-2 px-sm-2 px-2">
            <div class="service__card text-center" data-aos="fade-up" data-aos-delay="100">
              <img class="img-fluid mt-5" src="images/logo/logo.webp" alt="atozpay-logo">
              <div class="service__card--text text-left">
                <p class="h5">Atozpay</p>
                <span>
                  Atozpay melayani pembayaran digital online seperti BPJS, PDAM, LISTRIK, EMONEY,
                  PGN,PULSA,dan fitur QR Code scan antar HP
                </span>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col py-lg-0 py-md-2 py-sm-2 py-2 p-lg-1 px-md-2 px-sm-2 px-2">
            <div class="service__card text-center" data-aos="fade-up" data-aos-delay="200">
              <img class="img-fluid mt-5" src="images/logo/logo-atozogo.png" alt="atozgo-logo">
              <div class="service__card--text text-left">
                <p class="h5">Atozgo</p>
                <span>
                  AtozGO adalah layanan pesan antar makanan dengan jarak terdekat radius 300M untuk
                  perkantoran dan apartemen.
                </span>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col py-lg-0 py-md-2 py-sm-2 py-2 p-lg-1 px-md-2 px-sm-2 px-2">
            <div class="service__card text-center" data-aos="fade-up" data-aos-delay="300">
              <img class="img-fluid mt-5" src="images/logo/logo-atozagen.png" alt="atozagen-logo">
              <div class="service__card--text text-left">
                <p class="h5">Atozpay Agen</p>
                <span>
                  Maksimalkan penghasilan usahamu hingga jutaan rupiah dan dapatkan keuntungan di
                  setiap transaksi.
                </span>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col py-lg-0 py-md-2 py-sm-2 py-2 p-lg-1 px-md-2 px-sm-2 px-2">
            <div class="service__card text-center" data-aos="fade-up" data-aos-delay="400">
              <img class="img-fluid mt-5" src="images/logo/logo-createapp.png" alt="atozcreatapp-logo">
              <div class="service__card--text text-left">
                <p class="h5">Atozpay Createapp</p>
                <span>
                  Merupakan platform pengembangan aplikasi seluler Do-It-Yourself yang dibuat khusus
                  untuk bisnis kecil dan menengah.
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="about" class="abouts pd-section">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 col-md-8 text-sm-left text-center">
            <img src="images/logo/logo.webp" alt="atozpay-brand" width="250">
            <div class="text-left" data-aos="fade-up">
              <p class="pt-5">
                Semua pembayaran bisa dilakukan dengan mudah melalui Atozpay, yang pasti menjadi
                solusi terbaik transaksi keuangan digital kamu dengan lebih nyaman dan aman, mulai dari
                beli
                Pulsa, bayar Tagihan, QR code payment hingga Kirim Saldo yang pastinya #SemuaBisa
              </p>
              <!-- <a href="about.html" target="_blank" rel="noopener" class="hvr-underline-from-left"
                title="Selengkapnya">Lebih
                lagi</a> -->
              <router-link target="_blank" rel="noopener"  class="nav-link hvr-underline-from-left"  title="Selengkapnya" to="/About">Lebih lagi</router-link>
            </div>
          </div>
          <div class="abouts--img">
            <img class="img-fluid" src="images/bayar.png" alt="fintec-img">
          </div>
        </div>
      </div>
    </section>

     <section class="features pd-section">
      <div class="container">
        <h2 class="text-center mb-5">Transaksi Lebih Mudah dan Aman</h2>
        <div class="row">
          <div class="col-lg-3 col-md-6 col-sm-6 col-12 px-lg-1 px-md-2 px-sm-2 py-md-2 py-sm-2 py-2">
            <div class="features__card border-0" data-aos="fade-up" data-aos-delay="100">
              <div class="features__card--img py-4">
                <img class="img-fluid" src="images/icon/icon-pulsa.png" alt="img-feature">
              </div>
              <div class="p-3">
                <div class="h5">Pulsa &amp; Payment Point</div>
                <p>Sekarang bisa beli pulsa semua operator, Top up E–Money dan
                  pembayaran
                  Tagihan apapun dengan murah dan ngga pake lama.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6 col-12 px-lg-1 px-md-2 px-sm-2 py-md-2 py-sm-2 py-2">
            <div class="features__card border-0" data-aos="fade-up" data-aos-delay="200">
              <div class="features__card--img py-4">
                <img class="img-fluid" src="images/icon/icon-qr.png" alt="img-feature">
              </div>
              <div class="p-3">
                <div class="h5">QR Code Payment</div>
                <p>Atozpay menghadirkan pembayaran dan transfer saldo berbasis QR Code
                  yang pastinya lebih nyaman.</p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6 col-12 px-lg-1 px-md-2 px-sm-2 py-md-2 py-sm-2 py-2">
            <div class="features__card border-0" data-aos="fade-up" data-aos-delay="300">
              <div class="features__card--img py-4">
                <img class="img-fluid" src="images/icon/icon-promo.png" alt="img-feature">
              </div>
              <div class="p-3">
                <div class="h5">Promo Seru</div>
                <p>Temukan penawaran dan keuntungan lebih banyak dalam setiap
                  transaksi.</p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6 col-12 px-lg-1 px-md-2 px-sm-2 py-md-2 py-sm-2 py-2">
            <div class="features__card border-0" data-aos="fade-up" data-aos-delay="400">
              <div class="features__card--img py-4">
                <img class="img-fluid" src="images/icon/icon-tiket.png" alt="img-feature">
              </div>
              <div class="p-3">
                <div class="h5">Tiket Traveling Murah</div>
                <p>Traveling makin seru dengan E – Ticket Atozpay, mulai dari beli Tiket Kereta,
                  Shuttle Travel hingga Tiket Bus untuk semua tujuan tanpa biaya admin.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    name: "Atozpay"
  }
</script>

<style scoped>

</style>