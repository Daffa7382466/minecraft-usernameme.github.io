# minecraft-usernameme.github.io
echo "<h1>Hello World</h1>" > index.html

git add index.html
git commit -m "Add index.html"
git push
<!DOCTYPE html>
<html>
<head>
  <title>username minecraft</title>
  <style>
    span {
      display: block; /* Supaya jadi baris sendiri */
      margin-bottom: 24px; /* Atur jarak sesuai kebutuhan */
    }
      body {
                    background-color: rgb(189, 189, 189);
                }
  </style>
</head>
<body>
 <center> <!-- Halaman Password -->
  <div id="password-page">
    <h2>Masukkan Password</h2>
    <input type="password" id="password-input" placeholder="Password">
    <button onclick="checkPassword()">Masuk</button>
    <p id="error-message" style="color:red;"></p>
  </div>

  <!-- Halaman Konten Utama (disembunyikan dulu) -->
  <div id="main-page" style="display:none;">
    <!-- ...isi halaman utama kamu di sini... -->
    <h1><color style="color: rgb(101, 255, 96);">Sel<color style="color: rgb(0, 0, 0);">am<color style="color: rgb(255, 255, 255);">at Da</color>ta</color><color style="color: rgb(101, 255, 96);">ng!</color></h1>
    <strong><span><h1>username minecraft (daffa)</h1></span></strong>
    <h3>1.DaffaFarid0727 (java/bedrock)</h3>
    <h3>2.Daffa7382466 (bedrock)</h3>
  </div></center>

  <script>
  function checkPassword() {
    const password = document.getElementById('password-input').value.trim(); // trim untuk hapus spasi
    const correctPassword = 'daffauser'; // pastikan sama persis
    if (password === correctPassword) {
      document.getElementById('password-page').style.display = 'none';
      document.getElementById('main-page').style.display = 'block';
    } else {
      document.getElementById('error-message').innerText = 'Password salah!';
    }
  }
  </script>
</body>
</html>
