# Tag 标签
----
### 基础用法
使用```type```、```bg-color```、```color```、```border-color```和```round```属性来定义 Tag 的样式。
``` html
<xd-tag>普通</xd-tag>
<xd-tag type="primary">primary</xd-tag>
<xd-tag type="success">success</xd-tag>
<xd-tag type="warning" closable>warning</xd-tag>
<xd-tag type="error" round>error</xd-tag>
<xd-tag bg-color="#fc0" color="#e0439a" border-color="#fc0">自定义颜色</xd-tag>
```


### 属性
| 参数      | 说明    | 类型      | 可选值       | 默认值   |
|---------- |-------- |---------- |-------------  |-------- |
| type     | 类型   | string    |   primary,success,warning,error |     —    |
| round     | 圆角   | Boolean  |    — | false   |
| bg-color     | 背景颜色   | string    | 自定义 |     —    |
| color     | 文字颜色   | string    |  自定义 |     —    |
| border-color     | 边框颜色   | string    |   自定义 |     —    |

