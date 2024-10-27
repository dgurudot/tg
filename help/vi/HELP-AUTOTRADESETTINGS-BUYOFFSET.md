# **Bù trừ mua**

## Mục đích:

- Thiết lập này cho phép bạn điều chỉnh giá mua theo bù trừ cố định. Bù trừ mua sẽ được thêm vào giá mua đã chọn (Có thể là Ask, Bid hoặc Mark. Mặc định = Ask).

- Giao dịch sẽ được đặt ban đầu ở mức giá Buy nhận được trong tín hiệu. Nếu không được thực hiện trong vòng 5 giây, thì lần thử lại sẽ mua ở mức giá buy (Có thể là Ask, Bid hoặc Mark. Mặc định = Ask) cộng với bù trừ (mặc định là 0,05).

## Ví dụ:

- Tín hiệu mua $100 với Bid ở mức $99 và Ask ở mức $101. Nếu lệnh giới hạn ban đầu cho Buy không được khớp ở mức $100, thì lần thử lại sẽ diễn ra ở mức $101 + 0,05 = $101,05.
