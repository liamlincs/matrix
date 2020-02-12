# riot.im+matrix

1. 注册账号

访问https://riot.abc.com/
选最右侧的高级，其它matrix服务器，填https://matrix.abc.com
下一步，确认Matrix账号是在上一步填写的matrix.abc.com域名下，自定义用户名和密码
注册完成，进入后有错误提示框不用理会，点OK。

2. 登陆

如果退出了再登陆时，一定要注意登陆的matrix服务器是否为https://matrix.abc.com

3. 验证

Matrix 有个比较有趣的群聊设备验证流程，如果你打开 e2e 的开关，会要求所有在当前群聊里的设备，进行可信验证。验证方式是 A 用户发起后，B 用户会收到验证请求，同意后双方显示相同的 emoji 排列，需要通过第三方软件（钉钉/微信之类的）进行核对，都点了 confirm 后，验证通过。

如果有人使用了新设备接受群聊消息，会再次提醒群聊用户验证这个未知设备。

也就意味着，发给对方的信息，能确定送到可信设备上，即使有人知道了 B 用户的密码，B 用户的密钥 Key，但是如果不是 B 的同一台设备，其他人还是能发现 B “变了”。

4. 理念

Matrix（https://matrix.org/） 这款去中心化的 IM，解决了几个痛点。
第一，Telegram 有几个不完美的地方，不支持群组 e2e，先不说大群组的问题，三四人的私密群组是很需要 e2e 的。
第二，是 Telegram 如果有一天腐化了，是无法避免他作恶的。Matrix 是在安全和隐私方面走的更远的一款产品，并不是说每个人都需要去中心化的 IM，而是如果在意安全和隐私而使用 Telegram 的话，那么 Matrix 就会是一款更适合的产品。

5. Riot.im

是基于 Matrix 协议的开源 Web 产品。
