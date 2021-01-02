# Nexon_Kartrider_Api
넥슨 API를 이용해 닉네임->유저ID->매칭정보까지 불러옵니다. (메신저봇R)
//https://developers.nexon.com/kart/apiList

[사용된 기능]

1. {변수명}.startsWith({문자열}) //ex) a.startsWith("b"), 30번째줄
-> a(변수명)가 b로 시작할 때~

2. {변수명}.substr({숫자열}) //ex) a.substr(3), 32번째줄
-> 변수를 숫자만큼 자른다.

3. a = JSON.parse(a) || a = JSON.stringify(a) //37번째줄
-> stringify: 오브젝트 형식의 JSON을 문자열로 전환. 일반적인 방법으로 불러올 수 있다.
-> parse: 일반적인 문자열을 JSON형식을 변환. 배열을 불러오는 방식으로 불러올 수 있다.

4. a["b"]["c"] // 40번째줄
-> var a = {"b":{"c":"d"}};일 때 적합. 왼쪽이 Key값이고 오른쪽이 출력값이다.
-> 이와 비슷하게 출력값이 배열로 설정되어있을때는 {변수명}.{배열이름}[{배열순서}] 이다. //70번째줄
