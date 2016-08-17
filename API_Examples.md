##im.sessions.get
获取用户最近联系人列表
### URL
https://ictaddress/elgg/webservices/V1.1/im.sessions.get
### HTTP请求方式
POST
### 是否需要登录
是
所需登录参数，请携带：accessToken。
### 请求参数
    |必选|类型及范围|说明
----|----|----------|------
accessToken|true|string|授权访问token，在author.get中获得。
userid|true|string|当前用户的userid
offset|false|int|获取结果的偏移量
limit|false|int|获取结果的数量
### 注意事项
无
### 测试样例
无
### 返回结果
无
### 返回字段说明
无
### 其他
无
### 我要提问
提问[访问连接](http://www.sipsys.com)

