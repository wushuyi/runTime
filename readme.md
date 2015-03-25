# 用于返回 javascript 执行时间 的 工具类

* 用法:

>```javascript
    var time = new RunTime();
    setTimeout(function(){
        var resDataNum = time.getRunTimeJson();
        var resDataStr = time.getRunTimeJson('string');
        console.log(resDataNum);
        console.log(resDataStr);
    }, 3000);
 ```