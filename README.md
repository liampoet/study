Study
===

Reading
---
- ***[웹 브라우저와 웹 서버의 통신](https://aws.amazon.com/ko/blogs/korea/what-happens-when-you-type-a-url-into-your-browser/)***
  1. 웹 브라우저에 URL을 입력하고 Enter 키를 누릅니다.
  2. 웹 브라우저가 도메인의 IP 주소를 조회합니다. (먼저 캐시를 찾고, 그다음 DNS를 검색합니다.)
  3. 웹 브라우저가 찾은 IP 주소를 기반으로 서버와의 TCP 연결을 시작합니다.
  4. 웹 브라우저가 HTTP 요청을 서버로 전송합니다. (필요한 경우, HTTPS 보안 통신이 진행됩니다.)
  5. 웹 서버가 요청을 처리하고 응답을 다시 웹 브라우저로 전송합니다.
  6. 웹 브라우저가 전송 받은 콘텐츠를 렌더링합니다.

- [Channy님의 글쓰기와 소통방식](http://channy.creation.net/blog/1620#comment-807601)

- ***[TLS 핸드쉐이크](https://www.cloudflare.com/ko-kr/learning/ssl/transport-layer-security-tls/)***
