# WireShark
와이어샤크 파일 분석

파일 > IO Graph 분석, 트래픽증가 시간->내용 구체적으로 어떤 트래픽인가
프로토콜 별로 필터링 의심.
![image](https://github.com/user-attachments/assets/2c6bd3a9-d875-41da-9954-8156e5d9eeaf)

웹셸 업로드

get요청이 아닌것과 tcp 요청이 아닌것 tcp.dsport (tcp의 도착 포트가 80 인것)

tcp[13] == 18
