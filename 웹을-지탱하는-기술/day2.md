### 1. POST의 용도 3가지를 설명하시오. (141~145p)

### 2. 리소스 작성시 POST와 PUT 중에 POST를 쓰는게 적절한 이유는 무엇인가? (149p)

### 3. HEAD의 사용 용도는 무엇인가? (151p)

### 4. 다음 요청과 응답의 의미는 각각 무엇인가? (152p)

```markdown
요청
OPTIONS /list/item1 HTTP/1.1
Host: Example.com

응답
HTTP/1.1 200 OK
Allow: GET, HEAD, PUT, DELETE
```

### 5. 멱등성, 안전에 대해서 각각 설명하시오. (157p)

### 6. 멱등성과 안전을 기준으로 GET, HEAD, PUT, DELETE, POST를 분류하시오. (158p)

### 7. GET을 바르게 이용하고 있는지 판단하는 기준은 무엇인가? (164p)

### 8. 현재 토마토 가격은 100원이다. PUT으로 토마토 가격을 갱신할 때 다음 PUT 사용은 어떤 부분이 잘못됐는가? 또한 올바른 표현은 무엇인가? (165~167p)

```markdown
PUT /tomato HTTP/1.1
Host: example.com
Content-Type: text/plain; charset=utf-8

+50
```

### 9. 스테이터스 코드 1xx, 2xx, 3xx, 4xx, 5xx의 분류와 의미를 설명하시오. (173~174p)

### 10. 스테이터스 코드에서 첫 번째 숫자를 이용한 분류 방식의 장점을 모두 설명하시오. (174~175p)

### 11. 다음 응답 코드의 문제점은 무엇인가? (189p)

```markdown
HTTP/1.1 200 OK
Content-Type: application/xml

<error>
  <code>1001</code>
  <message>file not found</message>
</error>
```

### 12. HTTP에서 기술되는 일시는 어떤 표준시를 따르는가? (196p)

### 13. UTF-8로 선언된 xml 문서의 경우 `Content-Type` 헤더에 들어갈 알맞은 값은 무엇인가? (200~201p)

### 14. Content Negotiation이란 무엇인가? (202p)

### 15. 다음 2개의 메시지에 있는 10은 각각 몇 바이트인가? (205~206p)

```markdown
Content-Length: 10
```

```markdown
Transfer-Encoding: chunked
Content-Type: Text/plain; charset=utf-8

10
The brow fox ju
```

### 16. `WWW-Authenticate: Basic realm="Example.com` 를 클라이언트 입장에서 해석하시오. (207~208p)

### 17. URI Space를 설정하는 이유는 무엇인가? (208p)

### 18.SSL/TLS에서 제공하는 3가지 기능에 대해서 설명하시오. (211p)

### 19.`Expires`와 `Cache-Control`의 유효기간 표시법 차이는 무엇인가? (221p)

### 20.조건부 GET `If-Modified-Since` 와 `If-None-Match` 은 어떻게 구분하여 사용하는가? (226p)

### 21. Pipelining이란 무엇인가? (227p)
