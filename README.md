<!-- tambah_mahasiswa.html -->
<h2>Form Tambah Mahasiswa</h2>
<form action="proses_tambah_mahasiswa.php" method="POST">
  <label>Nama:</label><br>
  <input type="text" name="nama"><br>

  <label>NIM:</label><br>
  <input type="text" name="nim"><br>

  <label>Tanggal Lahir:</label><br>
  <input type="date" name="tgl_lahir"><br>

  <label>Program Studi:</label><br>
  <select name="prodi">
    <option value="1">Teknik Informatika</option>
    <option value="2">Sistem Informasi</option>
  </select><br>

  <label>Dosen Wali:</label><br>
  <select name="dosen">
    <option value="1">Dr. Andi</option>
    <option value="2">Dr. Sari</option>
  </select><br><br>

  <input type="submit" value="Simpan">
</form>
