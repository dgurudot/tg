# **Beli Offset**

## Tujuan:

- Pengaturan ini memungkinkan Anda untuk menyesuaikan harga beli dengan offset tetap. Offset beli akan ditambahkan ke harga beli yang dipilih (Bisa berupa Ask, Bid, atau Mark. Default = Ask).

- Transaksi akan ditempatkan pada harga Beli yang diterima dalam sinyal. Jika tidak tereksekusi dalam 5 detik, maka percobaan ulang akan membeli pada harga beli (Bisa berupa Ask, Bid, atau Mark. Default = Ask) ditambah offset (default 0,05).

## Contoh:

- Sinyal beli $100 dengan Bid $99 dan Ask $101. Jika limit order awal untuk Beli tidak terpenuhi pada $100, maka percobaan ulang akan dilakukan pada $101 + 0,05 = $101,05.