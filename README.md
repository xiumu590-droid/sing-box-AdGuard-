# sing-box-AdGuard-
sing-box [AdGuard]


DNS解析器
```
sing-box rule-set convert filter.txt --type adguard --output filter.srs
```


路由规则
```
{
    "rule_set": "AdGuard[dns解析]",
    "action": "reject",
    "method": "default",
    "no_drop": false
},
```

文本转二进制
* [AdGuard[dns解析]](https://github.com/xiumu590-droid/sing-box-AdGuard-/raw/refs/heads/main/filter.srs)

```
https://github.com/xiumu590-droid/sing-box-AdGuard-/raw/refs/heads/main/filter.srs
```
