# 마비노기 체형 확인 스크립트

```
javascript:$.ajax({url : '/dressroom/data/characterapi.asp',type : 'POST',contentType:"application/json",success : function(data){alert("키(10살:0 ~ 17살:1 상대수치) : " + data.gc_height + "\n몸무게(비만도) : " + data.gc_weight + "\n상체(근육) : " + data.gc_upper_weight + "\n하체 : " + data.gc_lower_weight);}});
```

[대표캐릭터 체형 확인](javascript:$.ajax({url : '/dressroom/data/characterapi.asp',type : 'POST',contentType:"application/json",success : function(data){alert("키(10살:0 ~ 17살:1 상대수치) : " + data.gc_height + "\n몸무게(비만도) : " + data.gc_weight + "\n상체(근육) : " + data.gc_upper_weight + "\n하체 : " + data.gc_lower_weight);}});)