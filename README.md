<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Modul 4-Hilda Aura Safitri Rachel</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="modul4styleee.css">
</head>
<body>
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">Perpustakaan My Lab</a>
      </div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li class="active"><a href="Beranda.html">Beranda</a></li>
          <li class="dropdown">
            <a class="dropdown-toggle" data-toggle="dropdown" href="#">Menu <span class="caret"></span></a>
            <ul class="dropdown-menu">
                <li><a href="Modul 1. index.html">Modul 1</a></li>
                <li><a href="Modul 2 Tabel.html">Modul 2</a></li>
                <li><a href="Modul 3 Inline.html">Modul 3-Inline</a></li>
                <li><a href="Modul 3 Internal.html">Modul 3-Internal</a></li>
                <li><a href="Modul 3 Eksternal.html">Modul 3-Eksternal</a></li>
                <li><a href="Modul 3 Variasi CSS.html">Modul 3-Variasi CSS</a></li>
                <li><a href="Modul 3 Gabungan Inline, Internal, Eksternal.html">Modul 3-Gabungan</a></li>
                <li><a href="Modul 4 Halaman Web.html">Modul 4-Halaman Web</a></li>
                <li><a href="Modul 5 HTML DOM.html">Modul 5-HTML DOM</a></li>
                <li><a href="Modul 5 Pameran Buku.html">Modul 5-Pameran Buku</a></li>
                <li><a href="Modul 6 Javascript Library.html">Modul 6-Javascript Library</a></li>
                <li><a href="Modul 7 Belajar PHP.html">Modul 7-Belajar PHP</a></li>
                <li><a href="Modul 7 Kalkulator.html">Modul 7-Kalkulator</a></li>
                <li><a href="Modul 7 Login.html">Modul 7-LogIn</a></li>
                <li><a href="Modul 7.html">Modul 7-Komentar</a></li>
                <li><a href="Modul 8 Database.html">Modul 8-Database</a></li>
            </ul>

          </li>
          <li><a href="Formulir.html">Form Keanggotaan</a></li>
        </ul>
      </div>
    </div>
  </nav>
  
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-4">
        <h2 style="color: #3f5730;">Selamat Datang di Perpustakaan My Lab</h2>
      </div>
      <div class="col-md-4">
        <h2 style="color: #6b9c4e;">Daftar Koleksi</h2>
        <table class="table table-bordered">
          <thead style="color:#3f5730">
            <tr>
              <th>No</th>
              <th>Judul Buku</th>
              <th>Pengarang </th>
              <th>Tahun Terbit</th>
              <th>No Panggil</th>
            </tr>
          </thead>
          <tbody style="color: #6b9c4e;">
            <tr>
                <td>1</td>
                <td>Re:</td>
                <td>Maman Suherman</td>
                <td>2014</td>
                <td>823 Suh r</td>
            </tr>
            <tr>
                <td>2</td>
                <td>RE:Dan Perempuan</td>
                <td>Maman Suherman</td>
                <td>2021</td>
                <td>823 Suh r</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Dilan: Dia adalah Dilanku tahun 1990</td>
                <td>Pidi Baiq</td>
                <td>2014</td>
                <td>823 Bai d</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="col-md-4">
        <h2 style="color: #6b9c4e">Form Keanggotaan</h2>
        <form style="color: #3f5730;">
          <div class="form-group">
            <label for="nama">Nama:</label>
            <input type="text" class="form-control" id="nama">
          </div>
          <div class="form-group">
            <label for="NIM">NIM:</label>
            <input type="text" class="form-control" id="alamat">
          </div>
          <button type="submit" class="btn btn-default">Submit</button>
        </form>
      </div>
    </div>
  </div>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <footer>
    <p>&copy; Built by Hilda Aura Safitri Rachel (210709034)</p>
    <p>Tugas Pengembangan Web Perpustakaan</p>
</footer>
</body>
</html>
