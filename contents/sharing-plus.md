# sharing-plus

分享当前页面到指定平台.

## 配置

```json
{
    "plugins": [
        "-sharing",
        "sharing-plus@0.0.2"
      ],

    "pluginsConfig": {
        "sharing": {
            "douban": false,
            "facebook": false,
            "google": false,
            "hatenaBookmark": false,
            "instapaper": false,
            "line": false,
            "linkedin": false,
            "messenger": false,
            "pocket": false,
            "qq": false,
            "qzone": false,
            "stumbleupon": false,
            "twitter": false,
            "viber": false,
            "vk": false,
            "weibo": false,
            "whatsapp": false,
            "all": [
                "facebook", "google", "twitter",
                "weibo", "instapaper", "linkedin",
                "pocket", "stumbleupon", "qq", "qzone"
            ]
        }
    }
}
```

## 效果

会在页面右上角创建一个链接图标
