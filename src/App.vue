<template>
  <div id="app">
    <header>
      <h1>Velg Dimas Dimensi</h1>
      <nav>
        <ul>
          <li><a href="#beranda">Beranda</a></li>
          <li><a href="#produk">Produk</a></li>
          <li><a href="#promo">Promo</a></li>
          <li><a href="#testimoni">Testimoni</a></li>
          <li><a href="#kontak">Kontak Kami</a></li>
          <li><a href="#blog">Blog</a></li>
        </ul>
      </nav>
    </header>

    <section id="hero">
      
      <h2>Velg Terbaru & Terpopuler 2024</h2>
    </section>

    <section id="promo">
      <h3>Promo Bulan Ini: Diskon hingga 50%!</h3>
      <ul>
        <li>Velg Racing</li>
        <li>Velg Custom</li>
        <li>Velg Klasik</li>
      </ul>
      <a href="#promo">Lihat Semua Promo</a>
    </section>

    <section id="produk">
  <h3>Kategori Produk</h3>
  <ul>
    <li>
      <img src="/images/gambar 2.jpg" alt="Velg Racing">
      <h4>Velg Racing</h4>
      <p>Desain modern dan sporty.</p>
    </li>
    <li>
      <img src="/images/gambar 3.jpg" alt="Velg Custom">
      <h4>Velg Custom</h4>
      <p>Velg custom sesuai selera.</p>
    </li>
    <li>
      <img src="/images/gambar 4.jpg" alt="Velg Klasik">
      <h4>Velg Klasik</h4>
      <p>Tampilan klasik dengan teknologi terkini.</p>
    </li>
  </ul>
  <a href="#produk">Lihat Semua Produk</a>
</section>


    <section id="keunggulan">
      <h3>Keunggulan Kami</h3>
      <ul>
        <li><h4>Kualitas Terjamin</h4><p>Uji kualitas ketat.</p></li>
        <li><h4>Harga Kompetitif</h4><p>Harga terbaik di pasar.</p></li>
        <li><h4>Pengiriman Cepat</h4><p>Pengiriman cepat ke seluruh Indonesia.</p></li>
        <li><h4>Garansi Produk</h4><p>Garansi resmi untuk setiap produk.</p></li>
      </ul>
    </section>

    <section id="testimoni">
      <h3>Testimoni Pelanggan</h3>
      <blockquote>
        <p>"Velg dari Toko Velg Impian membuat mobil saya terlihat keren! Kualitasnya sangat bagus dan pelayanannya luar biasa." - Andi, Jakarta</p>
      </blockquote>
      <blockquote>
        <p>"Saya sangat puas dengan velg custom yang saya pesan. Hasilnya sesuai dengan yang saya inginkan." - Rina, Surabaya</p>
      </blockquote>
      <a href="#testimoni">Lihat Lebih Banyak Testimoni</a>
    </section>

    <section id="cara-pesan">
      <h3>Cara Pesan</h3>
      <ol>
        <li><strong>Pilih Produk:</strong> Telusuri katalog produk kami.</li>
        <li><strong>Hubungi Kami:</strong> Konsultasi dan pemesanan.</li>
        <li><strong>Pembayaran:</strong> Metode pembayaran nyaman.</li>
        <li><strong>Pengiriman:</strong> Tunggu velg tiba di rumah.</li>
      </ol>
      <a href="#produk">Lihat Produk Sekarang</a>
    </section>

    <section id="kontak">
      <h3>Hubungi Kami</h3>
      <p><strong>Telepon:</strong> 0822-8773-6849</p>
      <p><strong>Email:</strong> adityadimas@gmail.com</p>
      <p><strong>Alamat:</strong> Jl. Air Dingin</p>
      <p><strong>Jam Operasional:</strong> Senin - Jumat, 09.00 - 18.00 WIB</p>
      <a href="#kontak">Kontak Kami</a>
    </section>

    <footer>
      <p>&copy; 2024 Dimas @All rights reserved.</p>
      <nav>
        <ul>
          <li><a href="#tentang">Tentang Kami</a></li>
          <li><a href="#kebijakan">Kebijakan Privasi</a></li>
          <li><a href="#syarat">Syarat & Ketentuan</a></li>
          <li><a href="#blog">Blog</a></li>
        </ul>
      </nav>
      <div class="sosial-media">
        <a href="#facebook">Facebook</a>
        <a href="#instagram">Instagram</a>
        <a href="#twitter">Twitter</a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 10px 0;
  text-align: center;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 10px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

#hero {
  background: url('./images/gambar 1.jpg') no-repeat center center/cover;
  color: #fff;
  height: 300px;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

#hero h2 {
  background: rgba(0, 0, 0, 0.5);
  padding: 20px;
}

section {
  padding: 20px;
}

section h3 {
  margin-top: 0;
}

section ul {
  list-style: none;
  padding: 0;
}

section ul li {
  background: #f4f4f4;
  margin: 10px 0;
  padding: 10px;
  border-left: 5px solid #333;
}

blockquote {
  background: #f9f9f9;
  padding: 10px;
  margin: 10px 0;
  border-left: 5px solid #333;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}

footer nav ul {
  list-style: none;
  padding: 0;
}

footer nav ul li {
  display: inline;
  margin: 0 10px;
}

footer nav ul li a {
  color: #fff;
  text-decoration: none;
}

footer .sosial-media a {
  margin: 0 10px;
  color: #fff;
  text-decoration: none;
}
</style>