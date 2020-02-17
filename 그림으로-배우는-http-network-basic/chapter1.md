# 1장 웹과 네트워크의 기본에 대해 알아보자

## 질문 목록

### 1. WWW을 구성하는 3가지 핵심 요소를 나열하고 각각에 대하여 설명하시오. (16p)

### 2. `http://user:pass@www.example.jp:80/dir/index.htm?uid=1#ch1` 과 같은 절대 URI를 구성하는 7가지 구성 요소를 밑줄로 구분해서 설명하시오. (33p)

### 3. 아래 리퀘스트 메시지에서 구성 요소 5가지를 구분하시오. (40p)

POST /form/entry HTTP/1.1  
Host: hackr.jp  
Connection: keep-alive  
Content-Type: application/x-www-form-urlencoded  
Content-Length: 16

name=ueno&age=37

### 4. 아래 리스폰스 메시지에서 구성 요소 5가지를 구분하시오. (42p)

HTTP/1.1 200 OK  
Date: Tue, 10 Jul 2012 06:50:15 GMT  
Content-Length: 362  
Content-Type: text/html

\<html>  
...

### 5. HTTP 지속 연결(keep alive)의 등장 배경과 장점에 대해서 설명하시오. (54~56p)

### 6. HTTP pipelining이 무엇인지 설명하시오. (57p)

### 7. HTTP는 stateless 프로토콜이다. stateless 프로토콜의 장점과 단점을 설명하시오. (58p)

### 8. 쿠키의 등장 배경과 쿠키 발행과 클라이언트의 쿠키 사용 과정을 설명하시오. (58~59p)

### 9. HTTP 메시지의 구성 요소 3가지를 나열하고 각각에 대하여 설명하시오. (62p)

### 10. 메시지 바디와 엔티티 바디의 차이점을 설명하시오. (65p)

### 11. Content Codings과 Chunked transfer Coding의 차이점을 설명하시오. (66~67p)

### 12. HTTP에서 Multipart 전송은 언제 사용하는가? 각각의 엔티티를 구분하기 위해 사용하는 문자열을 무엇이라 하는가? (68~70p)

### 13. Content Negotiation에 대하여 설명하시오. (73~74p)
