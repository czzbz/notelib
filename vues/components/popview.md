# popview

弹出容器

## Props

<!-- @vuese:popview:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|title|标题|`String`|`false`|-|
|type|类型|—|`false`|normal|
|transname|动画名称|—|`false`|slideup|
|transleave|离开动画|—|`false`|-|
|elclass|组件样式|—|`false`|-|
|closebt|是否显示关闭按钮|—|`false`|true|
|header|是否显示标题栏|—|`false`|true|
|leftlabel|左侧按钮标签|—|`false`|-|
|leftclass|左侧按钮样式|—|`false`|-|

<!-- @vuese:popview:props:end -->


## Events

<!-- @vuese:popview:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|clickleft|-|-|

<!-- @vuese:popview:events:end -->


## Slots

<!-- @vuese:popview:slots:start -->
|Name|Description|Default Slot Content|
|---|---|---|
|header|主体内容之上|-|
|default|主体内容|-|
|footer|底部内容|-|
|button|按钮区域|-|

<!-- @vuese:popview:slots:end -->


