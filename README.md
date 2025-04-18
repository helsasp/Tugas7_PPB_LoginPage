## Membuat Halaman Simple Login 📲
 
### 🔗Link Demo : https://youtu.be/vf2oYB2cn_4
### 💻 Penjelasan :

🔸 MainActivity.kt

1. Inheritance dari ComponentActivity<br>
MainActivity mewarisi ComponentActivity, class dasar untuk aktivitas Compose. 

2. Fungsi onCreate<br>
Fungsi utama yang dijalankan saat aplikasi dibuka. Di sini UI diatur menggunakan setContent. <br>

3. Penggunaan MyLoginTheme <br>
Mengatur tema aplikasi agar konsisten di seluruh tampilan.

4. Menampilkan LoginScreen() <br>
Fungsi Compose LoginScreen() dipanggil untuk menampilkan tampilan login di dalam Surface

🔸 LoginScreen.kt <br>
1. State untuk Email & Password <br>
email dan password menggunakan remember dan mutableStateOf agar UI bisa bereaksi saat nilai berubah.

2. Layout Kolom <br>
Menggunakan Column agar semua elemen UI ditata secara vertikal dan terpusat.

3. Ilustrasi Login<br>
Gambar login ditampilkan di bagian atas dengan Image dan painterResource.

4. Text Penyambutan <br>
Dua Text untuk menyapa pengguna dan memberi instruksi login.

5. Input Email dan Password <br>
Menggunakan OutlinedTextField untuk inputan dengan label dan dukungan pengamanan untuk password.

6. Tombol Login <br>
Button berwarna ungu dengan teks putih dan sudut bulat. Belum ada aksi saat diklik (masih kosong).

7. Tautan Lupa Password <br>
TextButton disediakan jika pengguna lupa password.

8. Login Alternatif <br>
Tulisan dan ikon untuk login via Facebook, Google, atau X (Twitter) menggunakan IconButton dengan gambar.

### 🖼️ App Preview : 
![image](https://github.com/user-attachments/assets/4e132b63-91b2-4720-8f4e-d8878df42782)

