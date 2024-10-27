# **Jumlah ReEntry**

## Tujuan: 

- Pengaturan ini memungkinkan Anda untuk menyesuaikan berapa kali kita akan mencoba lagi limit order dengan offset sebelum akhirnya menempatkan market order.

## Contoh:

- Jika jumlah retry Anda adalah 1, maka sinyal akan terlebih dahulu mencoba mengisi order pada harga yang diterima dalam sinyal. 
- Jika tidak terisi, maka hanya akan ada 1 retry (berdasarkan pengaturan jumlah retry dan dapat diubah) dan akan menggunakan Ask plus offset untuk sinyal Buy atau Bid minus offset untuk sinyal Sell. 
- Setelah percobaan retry habis, maka market order akan ditempatkan.