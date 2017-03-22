# spbNotes
商铺保笔记    

### 一.设置headers请求头信息    
1.jquery    
headers:{'Authorization':'Bearer ' + token'}
2.weui.js    
$.extend(headers, {'Authorization':'Bearer ' + token,'JB-Filename':encodeURI(this.name)})

### 二.自定义headers请求头   
[服务端需要对请求头字段进行Access-Control-Allow-Headers授权](http://www.cnblogs.com/holdon521/p/6225045.html)
### 三.请求头中带中文参数    
传递参数前先使用encodeURI(data)进行编码，服务端再进行一次反编码
