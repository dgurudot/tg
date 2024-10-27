# **ReEntry Offset**

## Tujuan: 

- Pengaturan ini memungkinkan Anda untuk menyesuaikan offset dari harga Ask (pada saat Beli) atau Bid (pada saat Jual). 
- Perdagangan akan ditempatkan pada harga Beli yang diterima dalam sinyal. 
- Jika tidak tereksekusi dalam waktu 5 detik, maka percobaan ulang akan membeli pada harga Ask ditambah offset (default adalah 0,05). 
- Demikian pula, jika sinyal jual diterima maka perdagangan akan ditempatkan pada harga jual yang diterima dalam sinyal tetapi jika itu tidak tereksekusi maka percobaan ulang akan berada pada harga Bid dikurangi offset (default adalah 0,05).

## Contoh:

- Sinyal beli $100 dengan Bid pada $99 dan Ask pada $101. Jika limit order awal untuk Beli tidak terpenuhi pada $100, maka percobaan ulang akan terjadi pada $101 + 0,05 = $101,05.

- Sinyal jual $200 dengan Bid pada $199 dan Ask pada $201. Jika limit order awal untuk Jual tidak terpenuhi pada $200, maka percobaan ulang akan dilakukan pada $199 - 0,05 = $198,95

