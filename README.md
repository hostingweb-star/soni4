<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Blog Basis Data — Sonia Kemala Putri</title>
  <style>
    :root{
      --bg-mid:#07112a;
      --bg-deep:#b24281;
      --accent:#b24281;
      --text:#eef6ff;
      --muted:#b8c9e8;
      --card:#081226;
      --radius:16px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:'Poppins',sans-serif;
      background:radial-gradient(circle at top left, rgba(110,168,255,0.08), transparent 40%),
                 radial-gradient(circle at bottom right, rgba(255,142,192,0.05), transparent 40%),
                 linear-gradient(180deg,var(--bg-mid),var(--bg-deep));
      color:var(--text);
      display:flex;justify-content:center;
      padding:32px 20px;
    }
    .wrap{width:100%;max-width:900px}

    header{
      display:flex;align-items:center;gap:18px;
      background:linear-gradient(135deg, rgba(255,255,255,0.08), rgba(255,255,255,0.02));
      padding:22px;border-radius:20px;border:1px solid rgba(255,255,255,0.08);
      box-shadow:0 10px 40px rgba(3,7,20,0.7), 0 0 60px rgba(178,66,129,0.3);
      backdrop-filter:blur(12px);
      margin-bottom:24px;
    }
    .avatar{width:110px;height:110px;border-radius:16px;overflow:hidden;
      border:3px solid rgba(178,66,129,0.5);flex-shrink:0;
      box-shadow:0 0 18px rgba(178,66,129,0.4)}
    .avatar img{width:100%;height:100%;object-fit:cover}
    .meta h1{font-size:24px;margin-bottom:6px;color:var(--accent)}
    .meta p{color:var(--muted);font-size:15px;margin-bottom:10px}
    .tags{display:flex;gap:8px;flex-wrap:wrap}
    .tag{background:rgba(255,255,255,0.05);padding:6px 12px;border-radius:999px;
      font-size:13px;color:var(--muted);border:1px solid rgba(255,255,255,0.06)}

    .post{
      background:linear-gradient(160deg, rgba(255,255,255,0.04), rgba(255,255,255,0.015));
      border-radius:var(--radius);
      padding:20px;margin-bottom:20px;
      border:1px solid rgba(255,255,255,0.05);
      box-shadow:0 8px 28px rgba(3,7,20,0.6), inset 0 0 40px rgba(178,66,129,0.08);
      transition:transform .3s ease, box-shadow .3s ease;
    }
    .post:hover{transform:translateY(-4px);box-shadow:0 10px 40px rgba(3,7,20,0.7),0 0 50px rgba(178,66,129,0.3)}
    .post h2{font-size:18px;margin-bottom:10px;color:#ffb3da}
    .post p,.post li{color:var(--muted);font-size:14px;line-height:1.6}
    .post ul{padding-left:20px;margin-top:8px}

    .img-container{text-align:center;margin:18px 0}
    .img-container img{
      max-width:80%;
      border-radius:12px;
      border:1px solid rgba(178,66,129,0.25);
      box-shadow:0 0 22px rgba(178,66,129,0.35);
      transition:transform .3s ease;
    }
    .img-container img:hover{
      transform:scale(1.04);
      box-shadow:0 0 30px rgba(178,66,129,0.45);
    }
    .img-caption{font-size:12px;color:#c6b5cc;font-style:italic;margin-top:6px;text-align:center}
    
    .hero {text-align: center;margin-top: 20px;}
    .hero iframe {
      width: 100%;
      max-width: 720px;
      height: 405px;
      border-radius: 12px;
      border: none;
      box-shadow: var(--card-shadow);}

    footer{margin-top:25px;text-align:center;color:var(--muted);font-size:13px}
    footer a{color:#ffb3da;text-decoration:none;font-weight:600}
    footer a:hover{text-decoration:underline}

    @media(max-width:700px){
      header{flex-direction:column;text-align:center}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">
        <img src="image2.jpg" alt="Foto Sonia Kemala Putri">
      </div>
      <div class="meta">
        <h1>SONIA KEMALA PUTRI</h1>
        <p>Mahasiswa Teknik Informatika — Universitas Buana Perjuangan Karawang</p>
        <div class="tags">
          <div class="tag">NIM : 24416255201103</div>
          <div class="tag">if24.soniaputri@mhs.ubpkarawang.ac.id</div>
          <div class="tag">Basis Data</div>
        </div>
      </div>
    </header>

      <article class="post">
        <h2>Post 1 : Contoh 5 Kasus Intersection</h2>
        <h3>Mahasiswa mengambil Mata Kuliah</h3>
        <div class="img-container">
          <img src="tabel1.png" alt="Contoh relasi tabel database">
          <p class="img-caption">Gambar: Contoh relasi tabel dengan Primary Key dan Foreign Key</p>
        </div>
        
        <h3>Pegawai mengikuti Proyek</h3>
        <div class="img-container">
          <img src="tabel2.png" alt="Contoh relasi tabel database">
          <p class="img-caption">Gambar: Contoh relasi tabel dengan Primary Key dan Foreign Key</p>
        </div>
        
        <h3>Siswa mengikuti Ekstrakurikuler</h3>
        <div class="img-container">
          <img src="tabel3.png" alt="Contoh relasi tabel database">
          <p class="img-caption">Gambar: Contoh relasi tabel dengan Primary Key dan Foreign Key</p>
        </div>
        
        <h3>Supplier menyuplai Barang</h3>
        <div class="img-container">
          <img src="tabel4.png" alt="Contoh relasi tabel database">
          <p class="img-caption">Gambar: Contoh relasi tabel dengan Primary Key dan Foreign Key</p>
        </div>
        
        <h3>Dokter melayani Pasien</h3>
        <div class="hero">
            <iframe src="https://www.youtube.com/embed/SqyUI_sog28?si=nZSIy1HMOrnWq6iJ" 
            title="YouTube video" allowfullscreen></iframe>
        </div>

    <article class="post">
        <h2>Post 2: Apa Itu Normalisasi pada ERD?</h2>
        <p><strong>Normalisasi</strong> adalah proses penyusunan tabel dalam database agar data tersimpan dengan efisien dan tidak terjadi pengulangan (redundansi).
            Proses ini dilakukan setelah pembuatan ERD (Entity Relationship Diagram) untuk memastikan bahwa setiap data ditempatkan pada tabel yang tepat dan saling terhubung secara logis.</p> 
        <ul>
          <br>Tujuan utamanya adalah <strong>agar struktur database lebih rapi, konsisten, dan mudah dipelihara.</strong>
        </ul>
    </article>


    <footer>
      © 2025 Blog Basis Data | <a href="https://www.ubpkarawang.ac.id" target="_blank">UBP Karawang</a>
    </footer>
