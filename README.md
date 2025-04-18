 Membuat Halaman Simple Login 📲
 
🔗Link Demo : https://youtu.be/vf2oYB2cn_4
💻 Penjelasan :

🔸 MainActivity.kt

    Inheritance dari ComponentActivity
    MainActivity mewarisi ComponentActivity, class dasar untuk aktivitas Compose.

    Fungsi onCreate
    Fungsi utama yang dijalankan saat aplikasi dibuka. Di sini UI diatur menggunakan setContent.

    Penggunaan MyLoginTheme
    Mengatur tema aplikasi agar konsisten di seluruh tampilan.

    Menampilkan LoginScreen()
    Fungsi Compose LoginScreen() dipanggil untuk menampilkan tampilan login di dalam Surface

🔸 LoginScreen.kt

    State untuk Email & Password
    email dan password menggunakan remember dan mutableStateOf agar UI bisa bereaksi saat nilai berubah.

    Layout Kolom
    Menggunakan Column agar semua elemen UI ditata secara vertikal dan terpusat.

    Ilustrasi Login
    Gambar login ditampilkan di bagian atas dengan Image dan painterResource.

    Text Penyambutan
    Dua Text untuk menyapa pengguna dan memberi instruksi login.

    Input Email dan Password
    Menggunakan OutlinedTextField untuk inputan dengan label dan dukungan pengamanan untuk password.

    Tombol Login
    Button berwarna ungu dengan teks putih dan sudut bulat. Belum ada aksi saat diklik (masih kosong).

    Tautan Lupa Password
    TextButton disediakan jika pengguna lupa password.

    Login Alternatif
    Tulisan dan ikon untuk login via Facebook, Google, atau X (Twitter) menggunakan IconButton dengan gambar.

🖼️ App Preview : 
