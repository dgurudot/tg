# **Sell Offset**

## Tujuan:

- Pengaturan ini memungkinkan Anda untuk menyesuaikan harga jual dengan offset tetap.
- Offset jual akan dikurangi dari harga jual yang dipilih (Bisa berupa Ask, Bid, atau Mark. Default = Bid).

- Transaksi akan ditempatkan pada harga Jual yang diterima dalam sinyal.
- Jika tidak tereksekusi dalam 5 detik, maka percobaan ulang akan menjual pada harga jual (Bisa berupa Ask, Bid, atau Mark. Default = Bid) dikurangi offset (default adalah 0,05).

## Contoh:

- Sinyal jual $200 dengan Bid $199 dan Ask $201.
- Jika limit order awal untuk Jual tidak terpenuhi pada $200, maka percobaan ulang akan dilakukan pada $199 - 0,05 = $198,95
