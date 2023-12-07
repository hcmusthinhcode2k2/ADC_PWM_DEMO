# ADC_PWM_DEMO
Ví dụ về HSPW
Ví dụ về ADC +PWM: đọc giá trị chiết áp bằng ADC và đặt độ sáng đèn LED đơn(vàng) bằng cách sử dụngPWM
Ngoài ra, LED1 & LED2 đang nhấp nháy đồng bộ mỗi giây bằng cách sử dụng TMR1 để cho biết bảng đó vẫn còn hoạt động
Sử dụng các công nghệ:
TMR1: khoảng thời gian 250 ms - để nhấp nháy LED1 và LED2 - đồng bộ
ADC1 Đầu vào - để đọc giá trị chiết áp
PWM1 Xuất ra đèn LED đơn RB14 (H,Ư
UART1 Đầu ra tới PC, 9600Baud, 8 bit, 1 điểm dừng, không chẵn lẻ
đầu vào:
chiết áp - giá trị được đọc qua ADC và được sử dụng cho chu kỳ nhiệm vụ của CPU
đầu ra:
Đèn LED RGB, kênh màu xanh lam - độ sáng thông qua xung điện, được điều khiển bằng chiết áp
kết xuất các giá trị ADC vàPWM hiện tại trên UART mỗi giây
sử dụng 9600 Baud, 8 bit, 1 stop-bit, không chẵn lẻ, không kiểm soát luồng trên thiết bị đầu cuối của bạn (ví dụ: PuTTY)
