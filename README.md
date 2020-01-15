# JWT-JSONWebToken-for-Spring
스프링에서 토큰 베이스 로그인 방법

### Token Based Auth (JWT)

Client[ID, Password] ← Token → Server[Token]

### Session based Auth

Client[ID, Password] ↔ Server[Cookie:SessionID] 



## Token

Header : Algorithm & Token Type

Payload : Data

Verify Signature : Hash(Header + Payload)