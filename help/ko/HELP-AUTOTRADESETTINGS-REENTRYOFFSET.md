# **재진입 오프셋**

## 목적: 

- 이 설정을 사용하면 매수 가격(매수 시점) 또는 매수 가격(매도 시점)의 오프셋을 조정할 수 있습니다. 
- 거래는 처음에 신호에서 수신한 매수 가격으로 배치됩니다. 
- 5초 이내에 실행되지 않으면 재시도는 매수 가격에 오프셋을 더한 가격으로 매수합니다(기본값은 0.05). 
- 마찬가지로 매도 신호가 수신되면 거래는 신호에서 수신한 매도 가격으로 배치되지만 실행되지 않으면 재시도는 매수 가격에서 오프셋을 뺀 가격으로 배치됩니다(기본값은 0.05).

## 예:

- 매수 가격이 $99, 매도가 $101인 매수 신호 $100. 매수에 대한 초기 제한 주문이 $100에서 체결되지 않으면 재시도는 $101 + 0.05 = $101.05에서 이루어집니다.

- 매수 가격이 $199, 매도가 $201인 매도 신호 $200. Sell에 대한 초기 제한 주문이 $200에서 채워지지 않으면 재시도는 $199 - 0.05 = $198.95에서 발생합니다.

