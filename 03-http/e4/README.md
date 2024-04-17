## Workshop(e4/w1)
```
장애가 아니라면 에러 로그 크기는 0. 그렇지 않다면 0으로 만들거나 장애라고 선언해야함.
장애 알람을 받으면 확인해야함. 그럴 필요가 없다면 받지 말아야함.
쓰지 않는 L4 는 반납해주세요.
주간업무 작성은 금요일 오전 11시까지!
```
* 위의 짧은 속담의 목록을 고려햐여 다음 요청에 응답하는 HTTP 서버를 작성하세요.
1. GET /proverbs/{id} 특정 속담을 반환합니다. 예) GET /proverbs/2 는 "장애 알람을 받으면 확인해야함. 그럴 필요가 없다면 받지 말아야함." 를 반환합니다.
2. GET /proverbs/ 는 404 Not Found 를 반환합니다.
3. GET 이 아닌 /proverbs 는 405 Method Not Allowed 를 반환합니다.

### 너무 쉽다면?
1. POST /proverbs 는 새로운 격언을 목록에 추가합니다. (파일이나 데이터베이스에 저장하지 마세요. 메모리에 추가하세요.)
2. DELETE /proverbs/{id} 는 격언을 삭제합니다.
3. encoding/json 패키지를 이용하여 json으로 응답하도록 수정하세요.

### 힌트
* 제공한 코드를 참고하세요.