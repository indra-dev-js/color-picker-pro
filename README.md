# Color-Picker-Pro

Aplikasi pemilih warna (color picker) yang ringan dan fokus untuk penggunaan mobile/webview. Dibuat pakai Vanilla JS (ES6 Classes) tanpa library eksternal yang berat, jadi sizenya kecil tapi fiturnya lengkap buat kebutuhan desain.

## Fitur Utama

- **Live Picker:** Support format HEX, RGB, CMYK, HSV, dan HSL.
- **Palette Manager:** Klik untuk simpan warna ke palet. Warna yang di palet bisa di-load balik ke picker cuma sekali klik.
- **Auto History:** Nyimpan warna-warna yang terakhir lo pilih secara otomatis.
- **Gradient Generator:** Ada tool buat bikin warna gradasi lengkap dengan beberapa preset siap pakai.
- **Native UI:** Drawer menu dengan overlay, appbar ala aplikasi mobile, dan sudah responsif buat layar HP.
- **Theme:** Support Dark Mode & Light Mode (ngikutin settingan sistem).

## Cara Pake

Tinggal buka file `index.html` di browser. Karena ini *single-file architecture*, lo nggak perlu setup server atau install npm. Cocok banget buat dibungkus jadi APK pake WebView.

## Teknis

- **Language:** HTML, CSS, JavaScript (Vanilla).
- **Pattern:** Class-based OOP.
- **Icons:** Lucide Icons (via CDN).
- **Storage:** Pake LocalStorage biar data palet dan riwayat nggak ilang pas browser di-refresh.

## Lisensi

Proyek ini dilisensikan di bawah **GNU General Public License v3.0 (GPL-3.0)**. 

Artinya lo bebas buat modifikasi dan sebarin ulang, tapi kalau lo rilis aplikasinya, lo juga harus buka source code-nya di bawah lisensi yang sama. Detailnya bisa cek di file [LICENSE](LICENSE).

---
*Maintained by [indra]*
