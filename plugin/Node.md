
\main.json : 入口文件

\libs : jar包

\modules : 模块入口
\modules\algorithm : 算法
\modules\ifdebug : 接口调试
\modules\convert : 转换

#说明
```json
{
  "name": "导航",                           // 当前页面名称
  "navigationDivList": [                    // 内容
    {                                       // 块
      "name": "搜索引擎",                   // 块名
      "type": 0,                            // 块类型
      "cols": 3,                            // 块列数
      "navigations": [                      // 块内容
        {                                   // 标签
          "name": "百度",                   // 标签名
          "url": "http://baidu.com/",       // url
          "fontColor": "#ffaa00"            // 颜色
        }
      ]
    }
  ]
}
```