# sing-box-AdGuard-
sing-box [AdGuard]


DNS解析器
文本转二进制:
```
sing-box rule-set convert filter.txt --type adguard --output filter.srs
```


路由规则:
```
{
    "rule_set": "AdGuard[dns解析]",
    "action": "reject",
    "method": "default",
    "no_drop": false
},
```

规则集:
```
{
    "type": "remote",
    "tag": "AdGuard[dns解析]",
    "format": "binary",
    "url": "https://github.com/xiumu590-droid/sing-box-AdGuard-/raw/refs/heads/main/filter.srs",
    "update_interval": "12h0m0s"
},
```


下载地址:
* [AdGuard[sing-box文档]](https://sing-box.sagernet.org/zh/configuration/rule-set/adguard/
)

