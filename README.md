
# 当前破解版并不是完美，不正确的配置，有风险被终止连接，并泄露节点和面板ip，请支持正版。
# 作者已永久停止更新。

# 使用教程
在soga_key处输入任意字符即可，如留空则为原版社区版本。

## 完整教程

[doc.sprov.xyz](https://doc.sprov.xyz/)

## 简单安装

``` bash
sudo bash < <(curl -Ls https://raw.githubusercontent.com/RManLuo/crack-soga-v2ray/master/install.sh)
```

## Docker安装

```
# 拉取镜像
docker pull rmanluo/crack-soga
# 运行镜像，参数请参考soga自带教程。
docker run --restart=always --name crack-soga -d -v /etc/soga/:/etc/soga/ --network host rmanluo/crack-soga \
--type=sspanel-uim \
--server_type=v2ray \
--api=webapi \
--webapi_url=https://xxx.com/ \
--webapi_mukey=xxx \
--soga_key=cracked_by_RMan \
--node_id=1
```

