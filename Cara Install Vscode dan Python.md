# Tutorial Instalasi VS Code dan Python
Berikut adalah langkah-langkah untuk menginstal Visual Studio Code (VS Code) dan Python di komputer Anda.

**1. Instalasi Visual Studio Code**

**Langkah 1**: Unduh VS Code

Buka situs resmi Visual Studio Code:
+ https://code.visualstudio.com/download.
+ Pilih versi sesuai sistem operasi Anda:

**Langkah 2**: Pasang VS Code
Windows:
+ Jalankan file ```.exe``` yang diunduh.
+ Centang opsi **Add to PATH** agar bisa menggunakan perintah VS Code di terminal.
+ **Klik Next** hingga selesai.

macOS:
+ Buka file ```.dmg``` yang diunduh.
+ Seret ikon VS Code ke folder **Applications**.

Linux:
+ Buka terminal dan jalankan:
```
cs
sudo dpkg -i code*.deb  # Untuk Debian/Ubuntu
sudo rpm -i code*.rpm   # Untuk Fedora/Red Hat
```
Langkah 3: Jalankan VS Code
Buka aplikasi Visual Studio Code.
2. Instalasi Python
Langkah 1: Unduh Python
Buka situs resmi Python:
https://www.python.org/downloads/.
Pilih versi Python terbaru sesuai sistem operasi Anda.
Langkah 2: Pasang Python
Windows:
Jalankan file .exe yang diunduh.
Centang Add Python to PATH sebelum mengklik Install Now.
macOS:
Jalankan file .pkg yang diunduh.
Ikuti langkah-langkah instalasi.
Linux:
Buka terminal dan jalankan:
bash
Salin
Edit
sudo apt update
sudo apt install python3
Langkah 3: Verifikasi Instalasi
Buka terminal atau Command Prompt.
Ketik perintah:
bash
Salin
Edit
python --version
atau
bash
Salin
Edit
python3 --version
Jika versi Python muncul, instalasi berhasil.
3. Integrasi Python dengan VS Code
Langkah 1: Pasang Ekstensi Python di VS Code
Buka VS Code.
Klik menu Extensions (ikon kotak di sidebar kiri).
Cari Python di kotak pencarian.
Klik Install pada ekstensi Python dari Microsoft.
Langkah 2: Konfigurasi VS Code
Buka file Python di VS Code atau buat file baru dengan ekstensi .py.
Jika diminta memilih interpreter, klik Select Python Interpreter dan pilih versi Python yang diinstal.
Tes dengan kode berikut:
python
Salin
Edit
print("Hello, World!")
Jalankan dengan menekan F5 atau Ctrl + Shift + P, lalu pilih Run Python File.
4. Tes Akhir
Buka terminal di VS Code dengan menekan Ctrl + `.
Ketik:
bash
Salin
Edit
python
Jika Python prompt muncul, instalasi dan konfigurasi selesai.
Anda sekarang siap menggunakan Python di Visual Studio Code untuk membuat program! 🚀






Anda bilang:
dalam bentuk repositori di github
