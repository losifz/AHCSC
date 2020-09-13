# AHCSC
### Auto Health Condition Self-Check
### 자동 건강상태 자가진단 매크로
#### 추가파일 설정 방법
```.env
  .env
  PUBLIC_KEY = "-----BEGIN PUBLIC KEY-----\n-----END PUBLIC KEY-----"
  HOUR = 시간
  MINUTE = 분
  SECOND = 초
  DAYOFWEEK_START = 시작 요일 설정(0 - 6)( 0 : 일요일, 6 : 토요일 )
  DAYOFWEEK_END = 마지막 요일 설정(0 - 6)( 0 : 일요일, 6 : 토요일 )
```

#### 서울시 소재 고등학교만 가능
```json
queue.json
{
  "이름":
    {
      "bd": "생년월일", 
      "pass": "비밀번호", 
      "school": "학교명" 
    }
}
```
