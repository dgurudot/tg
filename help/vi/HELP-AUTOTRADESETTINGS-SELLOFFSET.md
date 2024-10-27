# **Bù trừ bán**

## Mục đích:

- Thiết lập này cho phép bạn điều chỉnh giá bán theo bù trừ cố định.
- Bù trừ bán sẽ được trừ vào giá bán đã chọn (Có thể là Ask, Bid hoặc Mark. Mặc định = Bid).

- Giao dịch sẽ được đặt ban đầu ở mức giá Bán nhận được trong tín hiệu.
- Nếu không được thực hiện trong vòng 5 giây, thì nỗ lực thử lại sẽ bán ở mức giá bán (Có thể là Ask, Bid hoặc Mark. Mặc định = Bid) trừ đi bù trừ (mặc định là 0,05).

## Ví dụ:

- Tín hiệu bán là 200 đô la với Bid là 199 đô la và Ask là 201 đô la.
- Nếu lệnh giới hạn ban đầu cho Bán không được thực hiện ở mức 200 đô la, thì nỗ lực thử lại sẽ diễn ra ở mức 199 đô la - 0,05 = 198,95 đô la
