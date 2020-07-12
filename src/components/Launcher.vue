<template>
  <div>
    <div class="launcher">
        <button aria-label="close" id="btnHide" class="launcher__btn--hide">
            <i class="fas fa-times"></i>
        </button>
        <div class="launcher__wrapper">
            <img src="images/logo/launcher.webp" alt="Apps">
            <div class="launcher__wrapper__title">
                <p>Atozpay App</p>
                <span>Isi Pulsa dan PPOB Online Murah</span>
            </div>
            </div>
            <div class="p-2">
            <a href="https://play.google.com/store/apps/details?id=id.co.weypay" target="_blank" rel="noopener"
                class="launcher__btn--open">
                Buka
            </a>
        </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Launcher"
  }
</script>

<style scoped>

</style>