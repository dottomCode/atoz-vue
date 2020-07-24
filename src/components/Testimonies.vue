<template>
    <div>
        <section class="section-other pd-section">
            <div class="container">
                <div class="row text-center">
                    <div class="col-md-6">
                        <h2 class="mb-md-5 md-sm-4">Videos</h2>
                        <carousel :touchDrag="true" :mouseDrag="true" :margin="10" :merge="true" :center="true" :autoplay="true" :items="1" :loop="true" :nav="false" id="wrp-youtube" class="youtube owl-theme">
                            <div class="youtube__item" data-merge="1">
                                <div class="youtube__item--title">
                                    Atozpay Scan QR Code Payment
                                </div>
                                <a class="owl-video" href="https://youtu.be/SD-bnW9DO7M"></a>
                            </div>
                            <div class="youtube__item" data-merge="2">
                                <div class="youtube__item--title">
                                    Pemenang Program Hadiah Lebaran Atozpay Agen
                                </div>
                                <a class="owl-video" href="https://youtu.be/Gz5y7R23JTY"></a>
                            </div>
                            <div class="youtube__item" data-merge="2">
                                <div class="youtube__item--title">
                                    Testimoni pengguna atozGO
                                </div>
                                <a class="owl-video" href="https://youtu.be/1sRrksMGmUM"></a>
                            </div>
                            <div class="youtube__item" data-merge="2">
                                <div class="youtube__item--title">
                                    Testimoni Merchant atozGO
                                </div>
                                <a class="owl-video" href="https://youtu.be/c58mUl2eYmM"></a>
                            </div>
                            <div class="youtube__item" data-merge="2">
                                <div class="youtube__item--title">
                                    Atozpay Apps
                                </div>
                                <a class="owl-video" href="https://youtu.be/wL9A6dER28U"></a>
                            </div>
                            <div class="youtube__item" data-merge="2">
                                <div class="youtube__item--title">
                                    atozGO Apps
                                </div>
                                <a class="owl-video" href="https://youtu.be/gOUX5deB-BI"></a>
                            </div>
                        </carousel>
                    </div>
                    <div class="col-md-6">
                        <h2 class="wow fadeIn mb-md-5 md-sm-4">Testimonies</h2>
                        <carousel :nav="false" :autoplay="true" :loop="true" :items="1" :animateIn="slideInUp" :animateOut="slideOutUp" :touchDrag="true" :mouseDrag="true" id="client" class="testimony owl-theme">
                            <div class="item">
                                <div class="testimony__card py-md-3">
                                    <div class="col-sm-2 testimony__card--img">
                                        <img class="mx-md-auto mb-3 rounded-pill" src="images/img-testimony/Gunawan.webp" alt="img-testimony">
                                    </div>
                                    <div class="testimony__card--title py-sm-2 text-left px-3 col-sm-10 ml-auto mr-3 hvr-bubble-top">
                                        <blockquote class="blockquote pb-sm-0">
                                            <p>Semenjak pakai atozpay transaksi dan keuntungan lebih meningkat, juga jarang mengalami gangguan.</p>
                                            <div class="blockquote__footer text-sm-right text-center">
                                                <p class="mb-0">Gunawan</p>
                                                <span class="info">- Merchant Vika Cell</span><br>
                                                <span>Atozpay Agen</span>
                                            </div>
                                        </blockquote>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="testimony__card py-md-3">
                                    <div class="col-sm-2 testimony__card--img">
                                        <img class="mx-md-auto mb-3 rounded-pill" src="images/img-testimony/Grace.webp" alt="img-testimony">
                                    </div>
                                    <div class="testimony__card--title py-sm-2 text-left px-3 col-sm-10 ml-auto mr-3 hvr-bubble-top">
                                        <blockquote class="blockquote lead pb-sm-0 pb-3">
                                            <p>atozGO memudahkan aku untuk pesan makan siang. Tinggal buka aplikasinya. Tidak perlu antri lagi, makanannya langsung dianterin ke kantor</p>
                                            <div class="blockquote__footer text-sm-right text-center">
                                                <p class="mb-0">Grace</p>
                                                <span class="info">- Karyawati</span><br>
                                                <span>Pengguna atozGO</span>
                                            </div>
                                        </blockquote>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="testimony__card py-md-3">
                                    <div class="col-sm-2 testimony__card--img">
                                        <img class="mx-md-auto mb-3 rounded-pill" src="images/img-testimony/Marhamah.webp" alt="img-testimony">
                                    </div>
                                    <div class="testimony__card--title py-sm-2 text-left px-3 col-sm-10 ml-lg-auto ml-sm-0 mr-3 hvr-bubble-top">
                                        <blockquote class="blockquote lead pb-sm-0 pb-3">
                                            <p>Sebelum pakai atozGO pelanggan yang beli tidak begitu banyak, karena belum banyak yang tahu warung saya, sejak bergabung dengan atozGO transaksi makin meningkat, dan ramai banget.
                                            </p>
                                            <div class="blockquote__footer text-sm-right text-center">
                                                <p class="mb-0">Marhamah</p>
                                                <span class="info">- Soto Lamongan</span><br>
                                                <span>Merchant atozGO</span>
                                            </div>
                                        </blockquote>
                                    </div>
                                </div>
                            </div>
                        </carousel>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
import carousel from 'vue-owl-carousel'

export default {
    name: "Testimonies",
    components: {
        carousel
    }
}
</script>

<style scoped>

</style>