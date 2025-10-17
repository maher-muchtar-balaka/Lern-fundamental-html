# Lern-fundamental-html
<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Praktikum Pemrograman HTML - SMK Muhammadiyah 3 Tangerang Selatan</title>
  <style>
    /* Reset sederhana */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background: #ffffff;
      color: #222;
      line-height: 1.5;
      padding: 20px;
    }

    /* Header banner */
    .banner {
      background: #0b61b3;
      color: #fff;
      padding: 10px 16px;
      border: 3px solid #094f8a;
      display: flex;
      align-items: center;
      gap: 16px;
      margin-bottom: 18px;
    }
    .banner img.logo {
      width: 80px;
      height: 80px;
      object-fit: contain;
    }
    .banner .title {
      flex: 1;
      text-align: center;
    }
    .banner h1 {
      font-size: 20px;
      margin-bottom: 4px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    .banner p.sub {
      font-size: 12px;
    }

    /* Konten utama */
    .card {
      border: 1px solid #cfcfcf;
      padding: 18px;
      background: #fff;
    }

    .center { text-align: center; }

    h2 { margin: 12px 0; font-size: 18px; }
    h3 { margin: 10px 0; font-size: 16px; }

    section { margin-bottom: 18px; }

    /* Tabel elemen HTML */
    .tag-table, .data-table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 8px;
    }
    .tag-table th, .tag-table td, .data-table th, .data-table td {
      border: 1px solid #999;
      padding: 6px 8px;
      vertical-align: top;
      font-size: 13px;
    }
    .tag-table th, .data-table th {
      background: #f2f6fb;
      text-align: left;
    }

    .example { margin: 12px 0; padding: 8px; background: #fafafa; border: 1px solid #eee; }
    .example img { max-width: 120px; display: block; margin-top: 8px; }

    ul, ol { margin-left: 20px; margin-top: 6px; }

    /* Layout contoh */
    .layout-box {
      width: 100%;
      border: 1px solid #d1b14a;
      background: #f7e39a;
      margin-top: 12px;
      padding: 6px;
    }
    .layout-title {
      background: #f5d36e;
      padding: 8px;
      text-align: center;
      font-weight: 700;
      margin-bottom: 8px;
      border: 1px solid #d1b14a;
    }
    .layout-body {
      display: flex;
      gap: 12px;
    }
    .layout-left {
      width: 180px;
      border: 1px solid #d1b14a;
      padding: 8px;
      background: #fff6d9;
    }
    .layout-content {
      flex: 1;
      border: 1px solid #d1b14a;
      padding: 16px;
      background: #fff;
    }

    footer {
      margin-top: 18px;
      text-align: center;
      font-size: 13px;
      padding: 8px;
      border-top: 1px solid #ddd;
      color: #555;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <div class="banner">
    <img src="logo-smkm3.png" alt="Logo SMK Muhammadiyah 3 Tangerang Selatan" class="logo">
    <div class="title">
      <h1>SMK MUHAMMADIYAH 3 TANGERANG SELATAN</h1>
      <p class="sub">
        Program Keahlian Rekayasa Perangkat Lunak<br>
        Modul 0.1 - Praktikum Pemrograman HTML (HTML, PHP, dan CSS)
      </p>
    </div>
  </div>

  <!-- Konten utama -->
  <div class="card">
    <div class="center">
      <h2>Praktikum Pemrograman HTML</h2>
      <p>HTML, PHP, dan CSS</p>
      <p>Disusun oleh: <strong>Kevin Permana, S.Kom</strong></p>
    </div>

    <hr>

    <section>
      <h3>1. Tujuan</h3>
      <ul>
        <li>Peserta didik dapat memahami dasar pemrograman server-side menggunakan HTML.</li>
        <li>Peserta didik mengetahui sintaks-sintaks dasar HTML.</li>
        <li>Peserta didik mampu menyelesaikan permasalahan sederhana menggunakan HTML.</li>
      </ul>
    </section>

    <section>
      <h3>2. Dasar Teori</h3>
      <p>
        HTML (HyperText Markup Language) merupakan bahasa markup untuk menyusun halaman web
        yang dapat dibaca oleh browser. Browser seperti Google Chrome atau Firefox akan
        menerjemahkan kode HTML menjadi tampilan visual halaman web.
      </p>

      <table class="tag-table">
        <thead>
          <tr><th>Tag</th><th>Fungsi</th></tr>
        </thead>
        <tbody>
          <tr><td>&lt;h1&gt;–&lt;h6&gt;</td><td>Judul atau heading</td></tr>
          <tr><td>&lt;p&gt;</td><td>Paragraf/teks</td></tr>
          <tr><td>&lt;a&gt;</td><td>Hyperlink</td></tr>
          <tr><td>&lt;img&gt;</td><td>Menampilkan gambar</td></tr>
          <tr><td>&lt;br&gt;</td><td>Ganti baris</td></tr>
          <tr><td>&lt;hr&gt;</td><td>Garis pemisah horizontal</td></tr>
          <tr><td>&lt;strong&gt; / &lt;b&gt;</td><td>Teks tebal</td></tr>
          <tr><td>&lt;em&gt; / &lt;i&gt;</td><td>Teks miring</td></tr>
        </tbody>
      </table>
    </section>

    <section>
      <h3>3. Langkah Percobaan</h3>

      <h4>3.1 Heading HTML</h4>
      <div class="example">
        <h1>This is heading 1</h1>
        <h2>This is heading 2</h2>
        <h3>This is heading 3</h3>
        <h4>This is heading 4</h4>
        <h5>This is heading 5</h5>
        <h6>This is heading 6</h6>
      </div>

      <h4>3.2 Paragraf HTML</h4>
      <div class="example">
        <p>This is a paragraph.</p>
        <p>This is another paragraph.</p>
      </div>

      <h4>3.3 HTML Link</h4>
      <div class="example">
        <a href="https://www.w3schools.com" target="_blank">This is a link to W3Schools</a>
      </div>

      <h4>3.4 HTML Image</h4>
      <div class="example">
        <img src="logo-smkm3.png" alt="Logo SMKM 3">
        <p><small>SMK Muhammadiyah 3 Tangerang Selatan</small></p>
      </div>

      <h4>3.5 Garis Horizontal</h4>
      <div class="example">
        <p>The &lt;hr&gt; tag defines a horizontal rule:</p>
        <hr>
        <p>This is a paragraph.</p>
      </div>

      <h4>3.6 Ganti Baris</h4>
      <div class="example">
        <p>This is<br>a para<br>graph with line breaks.</p>
      </div>

      <h4>3.7 Format Teks HTML</h4>
      <div class="example">
        <p><b>This text is bold</b></p>
        <p><i>This text is italic</i></p>
        <p><u>This text is underlined</u></p>
        <p>This is <sub>subscript</sub> and <sup>superscript</sup>.</p>
      </div>

      <h4>3.8 HTML Table</h4>
      <table class="data-table">
        <thead>
          <tr><th>Firstname</th><th>Lastname</th><th>Points</th></tr>
        </thead>
        <tbody>
          <tr><td>Jill</td><td>Smith</td><td>50</td></tr>
          <tr><td>Eve</td><td>Jackson</td><td>94</td></tr>
          <tr><td>John</td><td>Doe</td><td>80</td></tr>
        </tbody>
      </table>

      <h4>3.9 HTML List</h4>
      <div class="example">
        <b>Unordered List</b>
        <ul>
          <li>Apples</li>
          <li>Bananas</li>
          <li>Lemons</li>
          <li>Oranges</li>
        </ul>

        <b>Ordered List</b>
        <ol>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
        </ol>
      </div>

      <h4>3.10 HTML Layout</h4>
      <div class="layout-box">
        <div class="layout-title">Main Title of Web Page</div>
        <div class="layout-body">
          <div class="layout-left">
            <strong>Menu</strong>
            <ul>
              <li>HTML</li>
              <li>CSS</li>
              <li>JavaScript</li>
            </ul>
          </div>
          <div class="layout-content">
            <p>Content goes here...</p>
          </div>
        </div>
        <div style="text-align:center; margin-top:8px; font-size:12px;">
          Copyright © SMK Muhammadiyah 3 Tangerang Selatan
        </div>
      </div>
    </section>

    <footer>
      Modul 0.1 - Praktikum Pemrograman HTML — Program Keahlian Rekayasa Perangkat Lunak
    </footer>
  </div>
</body>
</html>
