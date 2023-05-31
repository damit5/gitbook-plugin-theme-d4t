## 说明

基于[door](https://github.com/key7men/gitbook-plugin-theme-door)的微调。

## gitbook-plugin-theme-door
> 含有Header导航，Sidebar导航以及MiniMap导航的gitbook主题。

### 主题样式
![主题样式](./style.png)

### 使用方式
```json
{
  "plugins": [
    "splitter",
    "hide-element",
    "code",
    "theme-d4t",
    "-lunr",
    "-search",
    "-sharing",
    "search-pro-fixed"
  ],
  "variables": {
    "d4t": {
      "nav": [
        {
          "url": "xxxxx",
          "target": "_blank",
          "name": "论坛"
        },
        {
          "url": "xxxxx",
          "target": "_blank",
          "name": "登录"
        }
      ]
    }
  },
  "pluginsConfig": {
    "hide-element": {
      "elements": [".gitbook-link"]
    },
    "d4t": {
      "search-placeholder": "请输入关键字搜索",
      "logo": "./_media/logo.svg",
      "favicon": "./_media/favicon.ico"
    }
  }
}
```

