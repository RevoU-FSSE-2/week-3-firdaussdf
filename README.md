1. custom usingg @font face

html ini mengunakan font custom chunkfive pada h1 dan h2 yang di download dan disimpan di local font 

@font-face {
      font-family: "chunk-five";
      src: url('ChunkFive-Regular.otf') format('opentype');
    }

2.Text shadow to text
pada text h1 dan h2 menggunakan text shadow

3.responsive background image

background image pada halaman ini menyesuaikan ukuran perintah yang digunakan adalah sebagai berikut

 <style>
    body{
      background-image: url('latarbelakang.jpg');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      height: 100 vh;
      width:auto;
    }
  </style>


4.Assymetric grid

ada 4 bagian yang menggunakan assymetric grid dibawah h2 dengan perintah pada 
HTML

<section class="banner">
    
    <a href="#" class="promo">automotive</a>
    <a href="#" class="promo">electronics</a>
    <a href="#" class="promo">food and drugs </a>
    <a href="#" class="promo">agricultural</a>
</section>


css

.banner {
      display: grid;
      grid-template-columns: 2fr 1fr 1fr;
      grid-template-rows: minmax(30vh, 1fr) minmax(30vh, 1fr);
      grid-gap: 1rem;
  }
  
  .promo:first-child {
      grid-column: 1 / 2;
      grid-row: span 2;
  }
  
  .promo:nth-child(2) {
      grid-column: 2 / 4;
  }


5. advance form elements 

di halaman ini ada dua advanced form elemnet yaitu unuk form untuk tanggal dan provinsi

6 animation

ada efek animasi rotasi pada tulisan machine 

dan efek transisi pada gambar paling bawah denngan menggunakan opacity




link netifly

https://poetic-profiterole-a2e1d9.netlify.app/

