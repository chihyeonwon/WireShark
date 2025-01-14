#WireShark
와이어샤크 파일 분석

파일 > IO Graph 분석, 트래픽증가 시간->내용 구체적으로 어떤 트래픽인가
프로토콜 별로 필터링 의심.
![image](https://github.com/user-attachments/assets/2c6bd3a9-d875-41da-9954-8156e5d9eeaf)

웹셸 업로드

get요청이 아닌것과 tcp 요청이 아닌것 tcp.dsport (tcp의 도착 포트가 80 인것)

tcp[13] == 18

## 시스템 점검
![image](https://github.com/user-attachments/assets/2a88f3ac-8f86-44e6-a793-0c2bde3392f6)
![image](https://github.com/user-attachments/assets/5c86fc49-d053-4cec-ab95-13095a8ed70c)

/var/log/lastlog

oracle virtual Box 프로그램

# nmap 포트 스캔 ip 식별

사전식 공격 ncrack 패스워드 탈취

-> 패스워드 탈취 후 패스워드가지고 접속
-> 접속 후 ./ss로 무작위 대입 공격 진행

