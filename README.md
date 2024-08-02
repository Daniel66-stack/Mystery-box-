# Mystery Box Game

Welcome to the Mystery Box Game! Test your luck and see if you can find the hidden prizes before running out of attempts.

## Peraturan Permainan
1. **Nama Pemain**: Pemain harus memasukkan nama mereka sebelum memulai permainan.
2. **Jumlah Pilihan**: Setiap pemain memiliki 3 kali kesempatan untuk memilih kotak misteri.
3. **Hasil Pilihan**: Setiap kotak dapat berisi salah satu dari beberapa hasil, termasuk "zonk" (tidak mendapatkan hadiah) atau hadiah uang tunai (misalnya, "10rb", "15rb", atau "20rb").
4. **Kondisi Menang**: Pemain akan menang jika mereka menemukan hadiah uang tunai sebelum kesempatan habis.
5. **Kondisi Kalah**: Pemain akan kalah jika mereka telah memilih 3 kotak tanpa menemukan hadiah uang tunai.
6. **Notifikasi Hasil**: Setelah permainan selesai, hasilnya akan dikirim ke bot Telegram.

## Cara Bermain
1. **Masukkan Nama**: Pada awal permainan, akan muncul prompt untuk memasukkan nama pemain. Masukkan nama Anda dan klik tombol "Mulai Bermain".
2. **Memilih Kotak**: Setelah nama dimasukkan, akan muncul beberapa kotak misteri di layar. Klik pada kotak yang ingin Anda buka.
3. **Menunggu Hasil**: Setiap kotak yang dibuka akan menampilkan hasilnya, apakah "zonk" atau hadiah uang tunai. Anda memiliki 3 kesempatan untuk memilih kotak.
4. **Menang atau Kalah**: 
   - Jika Anda menemukan hadiah uang tunai dalam 3 kali pilihan, Anda akan menang, dan pesan "Winner" akan ditampilkan.
   - Jika Anda tidak menemukan hadiah uang tunai dalam 3 kali pilihan, Anda akan kalah, dan pesan "Game Over" akan ditampilkan.
5. **Hasil dan Pengiriman**: Setelah permainan selesai, hasil permainan beserta IP Anda akan dikirim ke bot Telegram untuk catatan.
6. **Restart**: Anda dapat memulai permainan baru dengan mengklik tombol "Main Lagi" setelah permainan berakhir.

## Integrasi Bot Telegram
Setelah permainan selesai, hasil permainan dan IP pengguna akan dikirim ke bot Telegram Anda. Untuk mengintegrasikan bot Telegram:
1. Ganti `telegramToken` dan `telegramChatId` dengan token dan chat ID bot Telegram Anda.
2. Bot akan menerima pesan dalam format berikut:
   - Nama pemain
   - IP pengguna
   - Hasil dari kotak yang dipilih

## Teknologi yang Digunakan
- HTML5
- CSS3
- JavaScript

## Cara Memulai
1. Clone repository ini.
   ```sh
   git clone https://github.com/your-username/mystery-box-game.git
   
