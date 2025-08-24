# 마비노기 체형 확인 스크립트

## 체형 확인 코드 내용
```javascript
$.ajax({url : '/dressroom/data/characterapi.asp',type : 'POST',contentType:"application/json",success : function(data){alert("키(10살:0 ~ 17살:1 상대수치) : " + data.gc_height + "\n몸무게(비만도) : " + data.gc_weight + "\n상체(근육) : " + data.gc_upper_weight + "\n하체 : " + data.gc_lower_weight);}});
```
## 북마크 버전
[대표캐릭터 체형 확인](javascript%3A%24.ajax%28%7Burl%20%3A%20%27%2Fdressroom%2Fdata%2Fcharacterapi.asp%27%2Ctype%20%3A%20%27POST%27%2CcontentType%3A%22application%2Fjson%22%2Csuccess%20%3A%20function%28data%29%7Balert%28%22%ED%82%A4%2810%EC%82%B4%3A0%20~%2017%EC%82%B4%3A1%20%EC%83%81%EB%8C%80%EC%88%98%EC%B9%98%29%20%3A%20%22%20%2B%20data.gc_height%20%2B%20%22%5Cn%EB%AA%B8%EB%AC%B4%EA%B2%8C%28%EB%B9%84%EB%A7%8C%EB%8F%84%29%20%3A%20%22%20%2B%20data.gc_weight%20%2B%20%22%5Cn%EC%83%81%EC%B2%B4%28%EA%B7%BC%EC%9C%A1%29%20%3A%20%22%20%2B%20data.gc_upper_weight%20%2B%20%22%5Cn%ED%95%98%EC%B2%B4%20%3A%20%22%20%2B%20data.gc_lower_weight%29%3B%7D%7D%29%3B)