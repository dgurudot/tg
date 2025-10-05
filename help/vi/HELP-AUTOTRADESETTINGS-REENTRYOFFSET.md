# **Độ lệch vào lại**

## Mục đích:

- Thiết lập này cho phép bạn điều chỉnh độ lệch giữa giá Bán (tại thời điểm Mua) và giá Mua (tại thời điểm Bán).
- Giao dịch ban đầu sẽ được đặt ở giá Mua nhận được trong tín hiệu.
- Nếu lệnh không được thực hiện trong vòng 5 giây, lệnh thử lại sẽ mua ở giá Bán cộng với độ lệch (mặc định là 0,05).
- Tương tự, nếu nhận được tín hiệu bán, lệnh sẽ được đặt ở giá bán nhận được trong tín hiệu, nhưng nếu lệnh không được thực hiện, lệnh thử lại sẽ ở giá Mua trừ đi độ lệch (mặc định là 0,05).

## Ví dụ:

- Tín hiệu mua 100 đô la với giá Mua 99 đô la và giá Bán 101 đô la. Nếu lệnh giới hạn ban đầu cho lệnh Mua không được khớp ở mức 100 đô la, lệnh thử lại sẽ được thực hiện ở mức 101 đô la + 0,05 = 101,05 đô la.

- Tín hiệu bán 200 đô la với giá Mua 199 đô la và giá Bán 201 đô la. Nếu lệnh giới hạn ban đầu cho lệnh Bán không được khớp ở mức 200 đô la, thì lệnh thử lại sẽ được thực hiện ở mức 199 đô la - 0,05 đô la = 198,95 đô la.

