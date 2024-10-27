# **Beli Offset**

## Tujuan: 

- Pengaturan ini memungkinkan Anda untuk menyesuaikan harga beli dengan offset tetap. Offset beli akan ditambahkan ke harga beli yang dipilih (Bisa berupa Ask, Bid atau Mark. Default = Ask).

- Perdagangan akan dilakukan pada awalnya dengan harga Beli yang diterima dalam sinyal. Jika tidak tereksekusi dalam waktu 5 detik, maka percobaan ulang akan membeli pada harga beli (Bisa berupa Ask, Bid atau Mark. Default = Ask) ditambah offset (default adalah 0,05). 

## Contoh:

- Sinyal beli $100 dengan Bid pada $99 dan Ask pada $101. Jika limit order awal untuk Beli tidak terpenuhi pada $100, maka percobaan ulang akan dilakukan pada $101 + 0,05 = $101,05.