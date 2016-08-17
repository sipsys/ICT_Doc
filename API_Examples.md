##im.sessions.get
###说明
获取某个用户最近联系人列表
###应用场景
该API用于第三方应用获取某个用户的最近联系人列表。在下面场景中会用到：

- 在第三方应用首次初始化时，需要获取会话列表时；
- 在第三方应用从最近会话列表中选择会话或者联系人时；
- 其他场景下。

### URL
>
>https://ictaddress/elgg/webservices/V1.1/im.sessions.get
>

### HTTP请求方式
POST
### 是否需要登录
是

所需登录参数，请携带：accessToken。

### 请求参数
    |必选|类型及范围|说明
----|----|----------|------
apikey|true|string|开发者的api key
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

