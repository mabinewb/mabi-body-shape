# 마비노기 체형 확인 스크립트

## 체형 확인 코드 내용
```javascript
$.ajax({url : '/dressroom/data/characterapi.asp',type : 'POST',contentType:'application/json',success : function(data){alert('키(10살:0 ~ 17살:1 상대수치) : ' + data.gc_height + '\n몸무게(비만도) : ' + data.gc_weight + '\n상체(근육) : ' + data.gc_upper_weight + '\n하체 : ' + data.gc_lower_weight);}});
```
## 북마크 버전
https://mabinewb.github.io/mabi-body-shape/

## 나이별 키 수치

8살 : -0.285714

9살 : -0.142857

10살 : 0

11살 : 0.142857

12살 : 0.285714

13살 : 0.428571

14살 : 0.571429

15살 : 0.714286

16살 : 0.857143

17살 : 1

18살 : 1.142857

19살 : 1.285714

20살 : 1.428571