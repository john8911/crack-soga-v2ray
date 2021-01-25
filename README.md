# 使用教程
在soga_key处输入任意字符即可，如留空则为原版社区版本。

## 完整教程

[doc.sprov.xyz](https://doc.sprov.xyz/)

## 简单安装

``` bash
sudo bash < <(curl -Ls https://raw.githubusercontent.com/john8911/crack-soga-v2ray/master/install.sh)
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

