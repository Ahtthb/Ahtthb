<!DOCTYPE html>
<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Shippori+Antique:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><link href="https://feeldreams.github.io/heihbd/style.css" rel="stylesheet" type="text/css" />
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  
<head>
<title>Selamat Ulang Tahun Bee</title>
<link rel="icon" type="image/x-icon" href="https://www.palingit.com/favicon.ico">
<meta name="description" content="HTML Replit Coding">
<!-- 
  Made with love by Yingg!
  
     Instagram: @ahtthb
     TikTok: @ahtthb
     Email: AhmadThoyib07@gmail.com
     
  Thanks to all <3
-->
</head>
<body>
  <font color="pink" face="Cambria"
	
   <!-- Ganti Audio di sini -->
   <audio src="file:///C:/Users/Ahmad%20T/Downloads/Music/[Gudanglagu456.CC]%20y2mate.com%20-%20Bulan%20Sutena%20%20Happy%20Birthday%20Official%20Music%20Video.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="file:///D:/FOTO/Bee/MVIMG_20200212_174206.jpg" id="wallpaper"/><div id="beneranblur"></div>
   </div>
   
   <div id='Content'>

     <div id="kadoIn">
       <!-- Tombol Surat --><img src="https://feeldreams.github.io/kadoin.png"/>
     </div>
     <p id="ket">Klik Kadonya!</p>

     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/bunga.gif" id="fotostiker"/>
         <img src="https://feeldreams.github.io/pusn.gif" id="fotostiker1"/>
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotostiker2"/>
         <img src="https://feeldreams.github.io/cilukba.gif" id="fotostiker3"/>
         <img src="https://feeldreams.github.io/pandakuning.gif" id="fotostiker4"/>
         <img src="https://feeldreams.github.io/emawh.gif" id="fotostiker5"/>
         
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotostiker6"/>
     </div>
     
     <p id="halo" class="halo"></p>
     
     <div><blockquote id='bq' data-text='㋡'>
       <p id="kalimat">Aku Ada Sesuatu Buat Bee Nih 🤣❤️</p>

       <p id="pesan1">Klik 4 Bunga di Bawah ini ya! 😆❤️</p>
       <div id="kolombaru">
         <li id="lv1"> 🌹</li>
         <li id="lv2"> 🌹</li>
         <li id="lv3"> 🌹</li>
         <li id="lv4"> 🌹</li>
       </div>

       <p id="pesan2">Tunggu bentar yaa...</p>
       <!-- Pesan -->
       <p id="pesan3">Ciee.. Nungguin yaa 🤣❤️</p>
       <p id="pesan4">Happy Birthday, </p>
       <p id="pesan5" class="gaya2">Nambah tua aja ya, hehe</p>
       <p id="pesan6" class="gaya2">Selamat ulang tahun, Sayang. Genap 24 tahun usia Bee hari ini ya. Maaf di pergantian menuju ulang tahun Bee, Boo tidak ada di samping Bee. Tidak memberi Bee kejutan di malam hari. Tidak membawakan Bee kue tart dengan lilin-lilin yang menyala di atasnya. Tidak menyanyakin Bee lagu'selamat ulang tahun' secara langsung. Tidak bisa bantu Tiup lilin-lilin yang menyala sampai padam setelah Bee mengucap doa dalam hati. Tidak juga dengan hadiah yang terbungkus rapi yang Bee harapkan.

Aku hanya bisa memberi Bee pesan ini di hari ulang tahun Bee. Mengucap doa dalam tulisan berserta harapan-harapan kebaikan untuk Bee, untuk hubungan kita.

Aku tahu ini aneh. Maafin Boo ya Bee. ❤️</p>
       <p id="pesan7" class="gaya2">Sehat selalu Sayang!</p>

       <p id="pesan8" class="gaya2">Canda Sayang wkwwk :v</p>
       <p id="pesan9" class="gaya2">Oh iya, semoga di hari spesialmu ini Bee dapat menjadi pribadi yang lebih baik yaa.. 🥳❤️</p>
       <p id="pesan10" class="gaya2">Happy Birthday Sayang nya Boo!! 🥳</p>

       <!-- Tombol Lanjut -->
       <p id="opsL">Klik untuk Lanjut</p>
     </blockquote></div>

     <!-- Tombol Kirim Pesan -->
     <div id="Tombol"><a id="By">&#128140; Lanjut</a></div>

     <!-- Pesan Tambahan -->
     <p id="katatambahan" class="sembunyi">Gajadi deh soalnya Bee belum Mandi wleee 😜</p>
     
     <!-- Pesan Ditolak -->
     <div id="pesanditolak">
       <img id="stikerditolak" src="https://feeldreams.github.io/weee.gif"/>
       <p id="kataditolak">Yaudah kalo gamau mh 😜</p>
     </div>

   </div>

<script>
  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2300, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); audio = new Audio('' + linkmp3.src); ftganti=0;fungsi=0;fungsiAwal=0;deffotostiker=fotostiker.src;function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-snowflake"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-snowflake"); if (heartArr.length > 100) {heartArr[0].remove()}},100);Content.style = "opacity:1;margin-top:16vh"; const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageHeight: 80,}); 
  
  document.getElementById("kadoIn").onclick = function() {if(fungsiAwal==0){audio.play();fungsiAwal=1;kadoIn.style="transition:all .8s ease;transform:scale(10);opacity:0";wallpaper.style="transform: scale(1.5);";ket.style="display:none";setTimeout(initengahan,300);setTimeout(inipesan,500)}}
  
  async function inipesan(){
    var { value: nama } = await swals.fire({
           title: 'Masukin Nama Kamu', input: 'text',
       });
       if(nama && nama.length < 11){
         window.nama = nama;
         vketikhalo="Hai, " + nama + " ✨";
         mulainama();
         } else {
           await swals.fire('Ups!', 'Nama tidak boleh kosong atau lebih dari 10 karakter, ya!');inipesan();
    }
  }

  //Variable Pertanyaan Akhir
  var tanya = 'Mau Kado Gak Nih? 😶❤️';
  var opstanya = 'Gak Mau Yaudah 😆';
  var tompositif = 'Mau';
  var tomnegatif = 'Engga';
    
    async function menuju(){pesanwhatsapp = "Makasii udah ngucapin " + nama + " ultah ><";await swals.fire('OK!', 'Kirim jawabannya ke WhatsApp aku, ya!', 'success');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;}
</script>
<script src="https://feeldreams.github.io/heihbd/script.js"></script>
<!-- Sampai Sini -->
</font>
</body>
  </html>
