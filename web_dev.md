### Web Dev

1. Web ?
world wide web = www or w3 : 인터넷(=네트워크)에 연결된 컴퓨터들을 통해 정보를 공유할 수 있는 공간. 

2. 인터넷 (Internet)
- Intranet : private  
- Extranet : private 
- Internet : global, public # web is a part of internet

3. HTTP (Hyper Text Transfer Protocol)
get: http://naver.com/rest-/v1.0 HTTP/1.1
-------------host---/------URI----------- 
---------------------URL------------------

클라이언트 <-> 서버의 Request <-> Response 사이의 규약
-> 클라이언트에서 서버 IP로 접속 ex) DNS에서 Naver.com IP 받아서 접속
Body: a.png In Response From 요청 주소 + Get ~/a.png / HTTP 1.1 


4. Protocol
- TCP: 패킷 -> 클라이언트, 시퀀스 O
- UDP: 시퀀스 X ex) 주소
- FTP: File Transfer
- DHCP: Dynamic Host Config 
- IMAP: Inter Message Access ex) 메일
- POP: Post Office # 메일함 서버와의 프로토콜 
- NNTP: Network News Transfer
- NTP: Network Time 
- SMTP: Simple Mail Transfer # 메일 보낼 때
- SNMP: Simple Network Manage # 네트워크 장비의 설정

5. HTTP Method
- GET
- HEAD
- POST
- PUT
- DELETE
- CONNECT
- OPTIONS ex) 캐시된 파일에 수정이 있는지 체크
- TRACE
- PATCH

Ex. Repose code
- 200: OK
- 202: Accepted
- 304: Not Modified
- 400: Bad Request NotAllowed
- 50x: Error

