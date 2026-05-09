GENTOO IN TERMUX ENHANCED - DOCUMENTATION
==========================================

# DESKRIPSI / DESCRIPTION

[ID] Ini adalah fork yang telah ditingkatkan dari script MrPurple666/gentoo-termux.
     Script ini dimodifikasi untuk efisiensi waktu dan manajemen file yang lebih cerdas.

[EN] This is an enhanced fork of the MrPurple666/gentoo-termux script.
     Modified for better time efficiency and smarter file management.

---

# RINGKASAN PERUBAHAN / CHANGELOG

1. DEPENDENCY CHECK (ID: Pengecekan dependensi proot & wget dipindahkan ke paling atas / 
   EN: Dependency checks for proot & wget moved to the very top).
2. TARBALL CACHING (ID: Deteksi otomatis file stage3 lokal untuk skip download / 
   EN: Auto-detect local stage3 files to skip download).
3. SAFE CLEANUP (ID: File tarball tidak dihapus otomatis agar bisa jadi cache / 
   EN: Tarball files are not auto-deleted, keeping them as cache).
4. PORTAGE OPTIMIZATION (ID: Skip update @world jika make.conf sudah ada / 
   EN: Skips hours of @world update if make.conf is already present).

---

# TUTORIAL INSTALASI / INSTALLATION GUIDE

[ID] BAHASA INDONESIA
---------------------
1. Update Termux & Install Paket:
   pkg update && pkg upgrade
   pkg install proot wget git -y

2. Clone Repository:
   git clone https://github.com/username-kamu/gentoo-termux-enhanced.git
   cd gentoo-termux-enhanced

3. Jalankan Script:
   chmod +x gentoo.sh
   ./gentoo.sh
   (Gunakan ./gentoo.sh -y untuk otomatis skip konfirmasi)

4. Masuk ke Gentoo:
   ./startgentoo.sh

[EN] ENGLISH VERSION
--------------------
1. Update Termux & Install Packages:
   pkg update && pkg upgrade
   pkg install proot wget git -y

2. Clone Repository:
   git clone https://github.com/sunandar3221/gentoo-termux-enhanced.git
   cd gentoo-termux-enhanced

3. Run Installer:
   chmod +x gentoo.sh
   ./gentoo.sh
   (Use ./gentoo.sh -y to skip all confirmations)

4. Start Gentoo:
   ./startgentoo.sh

---

# KREDIT / CREDITS
- Original Script: MrPurple666/gentoo-termux
- Inspired by: MFDGaming/ubuntu-in-termux
