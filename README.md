COOKIE
======

> 使用javascript来获取及设置cookie

## 如何使用
```javascript
// 首先在页面中引入COOKIE.js

//调用
COOKIE.has(name); //检测是否有名字为name的cookie
COOKIE.set(key,value,expire,path,domain); //设置一个新cookie，true表示设置成功，false表示设置失败
COOKIE.remove(name,path,domain); //删除名为name的cookie，true表示删除成功，false表示删除失败
COOKIE.get(name); //获取名为name的cookie的值
COOKIE.clear(path,domain); //清除所有cookie

````