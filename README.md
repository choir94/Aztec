# Langkah-langkah untuk Mendapatkan Role Apprentice di Server Discord Aztec

1. **Siapkan RPC dan Faucet untuk Node Aztec**
   - Sebelum menjalankan node Aztec, pastikan Anda memiliki akses ke RPC Ethereum Sepolia, RPC Sepolia Beacon, dan dana testnet dari Faucet Ethereum Sepolia.
   - **RPC Ethereum Sepolia**: Gunakan penyedia seperti Alchemy, Infura, atau node publik Sepolia. Contoh endpoint: `https://sepolia.infura.io/v3/YOUR_API_KEY` (ganti `YOUR_API_KEY` dengan kunci API Anda).
   - **RPC Sepolia Beacon**: Gunakan endpoint Beacon Chain untuk Sepolia, seperti dari penyedia layanan node. Contoh: `https://drpc.org/chainlist/eth-beacon-chain#eth-beacon-chain-sepolia`.
   - **Faucet Ethereum Sepolia**: Dapatkan ETH testnet untuk Sepolia dari faucet resmi, seperti:
     - [Google Cloud Sepolia Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia)
     - Pastikan Anda memiliki wallet yang mendukung Sepolia untuk menerima dana testnet.

2. **Jalankan Node Aztec**
   - Jalankan node Aztec di server Anda menggunakan one-click script berikut:
     ```bash
     wget -q https://raw.githubusercontent.com/choir94/Airdropguide/refs/heads/main/Aztec.sh && chmod +x Aztec.sh && ./Aztec.sh
     ```
   - Pastikan Anda telah mengatur konfigurasi node dengan RPC Ethereum Sepolia dan RPC Sepolia Beacon yang telah disiapkan.
   - Setelah node berjalan, tunggu sekitar 15 menit agar node dapat melakukan sinkronisasi dan siap digunakan.

3. **Cek Block Number dan Proof**
   - Setelah node selesai disinkronkan, periksa **block number** dan **proof** yang diperlukan untuk proses verifikasi.
   - Buka menu instalasi node Aztec (biasanya tersedia di terminal atau antarmuka node setelah script dijalankan).
   - Cari opsi atau perintah di menu instalasi untuk menampilkan **block number** (nomor blok terbaru dari node Anda) dan **proof** (data bukti yang dihasilkan node).
   - Catat informasi ini dengan cermat, karena akan diminta oleh bot Discord nanti.

4. **Masuk ke Server Discord Aztec**
   - Bergabunglah dengan Server Discord Aztec melalui link berikut: [Aztec Discord](https://discord.gg/aztec).
   - Setelah mendapatkan block number dan proof, masuk ke server Discord Aztec dan navigasikan ke saluran `operators | start-here`.

5. **Gunakan Perintah untuk Memulai**
   - Di dalam saluran `start-here`, ketikkan perintah berikut untuk memulai proses mendapatkan role Apprentice:
     ```
     /operator start
     ```
   - Setelah perintah dijalankan, bot akan menanyakan beberapa informasi.

6. **Masukkan Data yang Diperlukan**
   - Bot akan meminta beberapa informasi, seperti:
     - **Address** (Alamat wallet Anda yang digunakan di jaringan Sepolia)
     - **Block Number** (Nomor blok dari node Aztec Anda, yang telah Anda catat)
     - **Proof** (Bukti atau data yang diperlukan, yang telah Anda peroleh dari menu instalasi)
   - Masukkan setiap data satu per satu sesuai permintaan bot.

7. **Dapatkan Role Apprentice**
   - Setelah semua informasi dimasukkan dengan benar, Anda akan langsung mendapatkan role **Apprentice** di server Discord Aztec.

## Tips
- Pastikan node Anda sudah berjalan dan terhubung dengan baik ke RPC Ethereum Sepolia dan RPC Sepolia Beacon sebelum mencoba mendapatkan role.
- Periksa block number dan proof dengan teliti di menu instalasi untuk memastikan data yang Anda masukkan ke bot Discord akurat.
- Jangan khawatir jika bot tidak merespons langsung, itu normal selama proses sinkronisasi.
- Pastikan Anda memiliki izin untuk menjalankan script (`chmod +x`) dan koneksi internet stabil saat menjalankan one-click script.
- Simpan kredensial RPC dan wallet Anda dengan aman, serta pastikan Anda memiliki cukup ETH testnet dari faucet untuk operasi node.

## Informasi Lebih Lanjut
- Untuk panduan tambahan, pertanyaan, atau dukungan terkait node Aztec, bergabunglah dengan channel Telegram resmi: [Airdrop Node Telegram](https://t.me/airdrop_node).

Dengan langkah-langkah di atas, Anda sekarang sudah bisa mendapatkan role **Apprentice** di Discord Aztec setelah menunggu beberapa waktu dan memberikan data yang diperlukan!
