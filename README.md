# spbNotes
商铺保笔记
###一.设置headers请求头信息    
1.jquery    
headers:{'Authorization':'Bearer ' + token'}
2.weui.js    
$.extend(headers, {'Authorization':'Bearer ' + token,'JB-Filename':encodeURI(this.name)})

###二.自定义headers请求头   
[服务端需要对请求头字段进行Access-Control-Allow-Headers授权](http://www.cnblogs.com/holdon521/p/6225045.html)
