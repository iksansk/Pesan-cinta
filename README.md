# Pesan-cinta
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Pesan Cinta Untukmu</title>
  <style>
    body { margin:0; padding:0; background:linear-gradient(to top,#ffd6e7,#fff0f5); font-family:'Segoe UI',sans-serif; overflow:hidden; }
    .container { position:relative; text-align:center; padding:50px 20px; max-width:600px; margin:auto; background:rgba(255,255,255,0.95); border-radius:20px; box-shadow:0 8px 25px rgba(0,0,0,0.2); z-index:1; }
    h1 { color:#e60073; font-size:32px; }
    p { font-size:18px; line-height:1.7; color:#333; margin-top:20px; }
    .btn { margin-top:30px; background:#ff4d94; color:#fff; padding:14px 28px; border:none; border-radius:30px; text-decoration:none; font-size:16px; transition:0.3s ease; display:inline-block; }
    .btn:hover { background:#e60073; }
    .heart { position:absolute; width:20px; height:20px; background:red; transform:rotate(45deg); animation:float 8s infinite ease-in; opacity:0.7; z-index:0; }
    .heart::before,.heart::after { content:""; position:absolute; width:20px; height:20px; background:red; border-radius:50%; }
    .heart::before { top:-10px; left:0; }
    .heart::after { left:-10px; top:0; }
    @keyframes float {
      0% { transform:translateY(0) rotate(45deg); opacity:0.7; }
      100% { transform:translateY(-800px) rotate(45deg); opacity:0; }
    }
  </style>
</head>
<body>

  <!-- Audio Judika – Bukan Rayuan Gombal -->
  <audio autoplay loop hidden>
    <source src="https://archive.org/download/bukan-rayuan-gombal/Bukan%20Rayuan%20Gombal.mp3" type="audio/mpeg">
    Browser Anda tidak mendukung musik ini.
  </audio>

  <!-- Hati melayang -->
  <script>
    for (let i=0;i<40;i++) {
      const h=document.createElement('div');
      h.className='heart';
      h.style.left=Math.random()*100+'vw';
      h.style.animationDelay=Math.random()*10+'s';
      h.style.background=['#ff4d4d','#ff3399','#ff1a66'][Math.floor(Math.random()*3)];
      document.body.appendChild(h);
    }
  </script>

  <!-- Pesan cinta & tombol WhatsApp -->
  <div class="container">
    <h1>Untuk Sarina Lahagu 💌</h1>
    <p>
      Aa tahu, cinta ini tak bisa diukur dengan kata-kata.  
      Setiap hari bersamamu adalah hadiah terbesar.  
      Senyummu adalah cahaya, pelukanmu adalah rumah terbaik.  
      <br><br>
      Maafkan kekurangan aa, namun satu hal pasti:  
      cinta aa untukmu takkan pernah padam.  
      Aa akan selalu ada, menjaga, dan mencintaimu.  
      <br><br>
      Kamu adalah rumah bagi hati ini.  
      Aku mencintaimu, sekarang, besok, dan selamanya. ❤️
    </p>
    <a class="btn" href="https://wa.me/?text=Aku%20mencintaimu%20dengan%20tulus%20dan%20berjanji%20tidak%20akan%20pernah%20meninggalkanmu.%20❤️" target="_blank">
      Kirim ke WhatsApp
    </a>
  </div>

</body>
</html>
