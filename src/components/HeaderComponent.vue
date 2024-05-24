<template>
    <header>
      <h1>Toko Velg Impian</h1>
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
  </template>
  
  <script>
  export default {
    name: 'HeaderComponent'
  }
  </script>
  
  <style scoped>
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
  </style>