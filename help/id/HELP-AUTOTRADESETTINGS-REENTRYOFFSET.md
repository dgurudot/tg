# **ReEntry Offset**

## Tujuan:

- Pengaturan ini memungkinkan Anda untuk menyesuaikan offset dari harga Ask (saat Beli) atau Bid (saat Jual).
- Transaksi akan ditempatkan pada harga Beli yang diterima dalam sinyal.
- Jika tidak tereksekusi dalam 5 detik, maka percobaan ulang akan dilakukan pada harga Ask ditambah offset (default adalah 0,05).
- Demikian pula, jika sinyal jual diterima, maka transaksi akan ditempatkan pada harga jual yang diterima dalam sinyal, tetapi jika tidak tereksekusi, maka percobaan ulang akan dilakukan pada harga Bid dikurangi offset (default adalah 0,05).

## Contoh:

- Sinyal Beli $100 dengan Bid $99 dan Ask $101. Jika limit order awal untuk Beli tidak terpenuhi pada harga $100, maka percobaan ulang akan dilakukan pada harga $101 + 0,05 = $101,05.

- Sinyal Jual $200 dengan Bid $199 dan Ask $201. Jika limit order Jual awal tidak terpenuhi pada harga $200, maka percobaan ulang akan dilakukan pada harga $199 - 0,05 = $198,95

