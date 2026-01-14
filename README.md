# sing-box-AdGuard-
sing-box [AdGuard]


DNS解析器
文本转二进制:
```
sing-box rule-set convert 文件名.txt --type adguard --output 文件名.srs
```

规则集:
```
{
    "type": "remote",
    "tag": "AdGuard[dns解析]",
    "format": "binary",
    "url": "https://github.com/xiumu590-droid/sing-box-AdGuard-/raw/refs/heads/main/另类.srs",
    "update_interval": "12h0m0s"
},
```


文档:
* [AdGuard[sing-box文档]](https://sing-box.sagernet.org/zh/configuration/rule-set/adguard/
)

