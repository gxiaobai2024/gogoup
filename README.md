# gogoupCloudflare 部署
•创建pages：点击workers和pages，选择pages部署。连接github仓库，选择新建的项目仓库，然后点击部署。

•绑定自定义域名：以防止page分配的域名被屏蔽。

•设置变量：UUID，PROXY_IP, TR_PASS

•绑定KV命名空间：名称随便但不能含有bpb等敏感词

•重试部署pages

BPB面板设置
•部署成功后，打开浏览器输入:https://[自定义域名]或者你的项目地址,后面加上/panel检查是否能正常访问BPB面板.

•修改BPB面板密码

•配置BPB面板参数

常用IP获取方式
cleanIP/优选IP：地址1  地址2  地址3  地址4
PROXYIP：点击进入1https://www.nslookup.io/domains/bpb.yousef.isegaro.com/dns-records/
点击进入2https://ipdb.030101.xyz/bestproxy/
