<template>
  <main>
    <div class="header">
      <div class="container">
        <div class="headerLogo">
          <a href="index.html">
            <img style="width: 480px;" src="@/assets/images/anadolu_kafkasya_logo.png" alt="AG">
          </a>
        </div>
      </div>
    </div>

    <section class="content">
      <div class="container">
        <div class="companyInfo">
          <ul>
            <li><span class="left">Şirket Unvanı</span><b>:</b><span class="right">ANADOLU BİLİŞİM HİZMETLERİ A.Ş.</span></li>
            <li><span class="left">Telefon Numarası</span><b>:</b><span class="right">+90 216 578 85 00</span></li>
            <li><span class="left">E-Posta</span><b>:</b><span class="right">info@abh.com.tr</span></li>
            <li><span class="left">Adres</span><b>:</b><span class="right">Fatih Sultan Mehmet Mahallesi, Balkan Cad. Buyaka E Blok No:58 Tepeüstü Ümraniye / İstanbul</span></li>
          </ul>
        </div>
        <div class="links">
          <!-- Linkler eklenebilir -->
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
@import '@/assets/styles/main.css';
</style>