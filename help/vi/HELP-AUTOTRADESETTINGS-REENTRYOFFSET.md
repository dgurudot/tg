# **Bù trừ ReEntry**

## Mục đích:

- Thiết lập này cho phép bạn điều chỉnh bù trừ từ giá Ask (tại thời điểm Buy) hoặc Bid (tại thời điểm Sell).
- Giao dịch sẽ được đặt ban đầu tại giá Buy nhận được trong tín hiệu.
- Nếu không được thực hiện trong vòng 5 giây, thì nỗ lực thử lại sẽ mua tại Ask cộng với bù trừ (mặc định là 0,05).
- Tương tự, nếu nhận được tín hiệu bán thì giao dịch sẽ được đặt tại giá sell nhận được trong tín hiệu nhưng nếu không được thực hiện thì nỗ lực thử lại sẽ là Bid trừ bù trừ (mặc định là 0,05).

## Ví dụ:

- Tín hiệu mua $100 với Bid là $99 và Ask là $101. Nếu lệnh giới hạn ban đầu cho Buy không được khớp tại $100, thì nỗ lực thử lại sẽ diễn ra tại $101 + 0,05 = $101,05.

- Tín hiệu bán $200 với Bid là $199 và Ask là $201. Nếu lệnh giới hạn ban đầu cho lệnh Bán không được khớp ở mức $200, thì lệnh thử lại sẽ diễn ra ở mức $199 - 0,05 = $198,95

