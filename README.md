# Catat by Rumah Andalan — Rilis Resmi Aplikasi

Repositori ini khusus menyimpan **paket instalasi resmi (rilis biner)** untuk **Catat by Rumah Andalan** (*Aplikasi Pengelola Leads, WhatsApp & Donasi*), terpisah dari repositori *source code* utama.

> Aplikasi web & pembaruan tampilan/fitur otomatis tersinkron secara *live* melalui `https://catat.rumahandalan.com`. Pemasangan ulang APK/EXE hanya diperlukan bila ada pembaruan modul *native* atau versi rilis baru.

---

## Unduh Rilis Terbaru (`v1.0.0`)

Silakan unduh file sesuai perangkat Anda melalui halaman [**Releases v1.0.0**](https://github.com/anuandahpokoknya/Catat-by-RumahAndalan_Release/releases/tag/v1.0.0):

| Platform | Nama Berkas | Jenis | Ukuran |
| :--- | :--- | :--- | :--- |
| **Android** | [`Catat.by.Rumah.Andalan.apk`](https://github.com/anuandahpokoknya/Catat-by-RumahAndalan_Release/releases/download/v1.0.0/Catat.by.Rumah.Andalan.apk) | APK Android (Capacitor) | 8.01 MB |
| **Windows** | [`Catat.by.Rumah.Andalan.v1.0.0.exe`](https://github.com/anuandahpokoknya/Catat-by-RumahAndalan_Release/releases/download/v1.0.0/Catat.by.Rumah.Andalan.v1.0.0.exe) | Installer Setup Windows (NSIS) | 2.57 MB |
| **Windows (Portable)** | [`Catat.by.Rumah.Andalan.v1.0.0.Portable.exe`](https://github.com/anuandahpokoknya/Catat-by-RumahAndalan_Release/releases/download/v1.0.0/Catat.by.Rumah.Andalan.v1.0.0.Portable.exe) | Aplikasi Portable (Tanpa Install) | 12.24 MB |

---

## Panduan Pemasangan

### 1. Android (`Catat.by.Rumah.Andalan.apk`)
1. Unduh file **`Catat.by.Rumah.Andalan.apk`** dari halaman Releases.
2. Ketuk file `.apk` yang sudah terunduh; bila diminta izin *Install unknown apps*, aktifkan izin untuk browser/pengelola file Anda.
3. Setelah terpasang, buka aplikasi **Catat** dan masuk menggunakan akun Google/kredensial tim Anda.
4. Izinkan **Notifikasi** agar pemberitahuan *push* (persetujuan akun, donasi, dan tugas) dapat langsung diterima.

### 2. Windows (`v1.0.0.exe` atau `v1.0.0.Portable.exe`)
- **Mode Installer (`Catat.by.Rumah.Andalan.v1.0.0.exe`):** Jalankan installer, ikuti langkah pemasangan hingga selesai, lalu buka **Catat by Rumah Andalan** dari Start Menu atau Desktop.
- **Mode Portable (`Catat.by.Rumah.Andalan.v1.0.0.Portable.exe`):** Langsung jalankan file `.exe` tanpa perlu proses instalasi.
- *(Catatan: Apabila muncul peringatan **Windows Defender SmartScreen**, klik **More info → Run anyway** karena aplikasi didistribusikan secara internal tanpa sertifikat EV komersial.)*

---

## Verifikasi Integritas Berkas (SHA-256)

Untuk memastikan berkas unduhan asli dan tidak korup, cocokkan *checksum* SHA-256 berikut:

| Berkas | SHA-256 |
| :--- | :--- |
| `Catat.by.Rumah.Andalan.apk` | `325740A2A457BD1E29ADE148662B01FAA6DAD3C97082D29CC12637ACB50B8BD6` |
| `Catat.by.Rumah.Andalan.v1.0.0.exe` | `FAC6C43AE9BA3FF81953B843421F8EBFF978AEE2C5CE8F57C296A0B2A8CDECCF` |
| `Catat.by.Rumah.Andalan.v1.0.0.Portable.exe` | `EBB8B97BB51B02B14CB2D3C1783D1235C7BDCF329824ABB1122B19543FE4F42F` |

Cara memeriksa di PowerShell Windows:
```powershell
Get-FileHash .\Catat.by.Rumah.Andalan.v1.0.0.exe -Algorithm SHA256
```

---

## Dukungan & Kontak
- **Aplikasi Web:** https://catat.rumahandalan.com
- **Email Dukungan:** support@rumahandalan.com
