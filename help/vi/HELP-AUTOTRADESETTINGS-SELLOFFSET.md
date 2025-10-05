# **Bù trừ Bán**

## Mục đích:

- Thiết lập này cho phép bạn điều chỉnh giá bán theo bù trừ cố định.
- Bù trừ Bán sẽ được trừ vào giá bán đã chọn (Có thể là Giá chào bán, Giá chào mua hoặc Giá đánh dấu. Mặc định = Giá chào mua).

- Giao dịch ban đầu sẽ được đặt ở mức Giá bán nhận được trong tín hiệu.
- Nếu lệnh không được thực hiện trong vòng 5 giây, lệnh thử lại sẽ được bán ở mức giá bán (Có thể là Giá chào bán, Giá chào mua hoặc Giá đánh dấu. Mặc định = Giá chào mua) trừ đi bù trừ (mặc định là 0,05).

## Ví dụ:

- Tín hiệu bán 200 đô la với Giá chào mua là 199 đô la và Giá chào bán là 201 đô la.
- Nếu lệnh giới hạn ban đầu cho lệnh Bán không được khớp ở mức 200 đô la, thì lệnh thử lại sẽ được thực hiện ở mức 199 đô la - 0,05 = 198,95 đô la.
