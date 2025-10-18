# DAPCOIN Airdrop Bot 🤖

> A bot for automating DapCoin airdrop interactions, including wallet generation, registration, and daily check-in with proxy support.

## 🛑 PENTING: LISENSI DAN HAK CIPTA

Seluruh isi repositori ini dilindungi hak cipta (Copyright) oleh [https://t.me/AirdropWhalesAcademy]. Kode ini didistribusikan di bawah lisensi **UNLICENSED**.

**Anda tidak diizinkan untuk:**
* Membuat ulang (remake), menyalin, atau mendistribusikan ulang kode ini.
* Memodifikasi kode ini untuk tujuan komersial atau publikasi ulang tanpa izin tertulis.

## Requirements

1.  **Node.js** (version 16 or higher)
2.  **npm** (Node package manager)

## Installation

To get started with the DAPCOIN Airdrop Bot:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/whale2earn/Dapcoin-Angry-Auto-Reff.git
    cd Dapcoin-Angry-Auto-Reff
    ```

2.  **Install the dependencies:**
    ```bash
    npm install
    ```

## Configuration

Before running the bot, set up your optional configuration files.

### 1. proxy.txt (Optional)

File ini hanya diperlukan jika Anda memilih untuk menggunakan proxy saat menjalankan bot. Bot Anda mendukung mode Rotating (berputar) dan Static (menggunakan proxy satu kali) untuk format HTTP/HTTPS dan SOCKS5.

* Buat file **`proxy.txt`** di *root* proyek Anda.
* Tambahkan detail proxy Anda. Setiap baris harus memiliki format:
    ```
    host:port:username:password
    ```
* **Example:**
    ```
    123.45.67.89:8888:userku:passku
    123.45.67.89:8889:userlain:passlain
    ```

## Running the Bot

To start the bot, run the following command:

```bash
node dapcoin.js

When you start, the script will guide you through the configuration prompts:

Pilihan Proxy: Apakah Anda ingin menggunakan proxy (proxy.txt).

Jenis Proxy: Rotating atau Static.

Jumlah Akun: Berapa banyak akun yang akan diproses.

Kode Undangan: Kode referral yang akan digunakan.
