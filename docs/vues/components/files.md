# files

文件列表

## Props

<!-- @vuese:files:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|value|-|—|`false`|-|
|saveapi|保存API|`String`|`false`|/base/setfile|
|delapi|删除API|`String`|`false`|/base/delfile|
|editable|是否可以编辑|—|`false`|-|
|multiple|是否多选|—|`false`|true|
|maxsize|最大上传容量|—|`false`|20|
|maxamt|最大数量|—|`false`|0|
|ext|提交时的扩展数据|—|`false`|-|
|autoupload|选择后是否自动上传|—|`false`|true|
|uploadapi|上传API|—|`false`|/base/upload|
|download_prefix|下载地址前缀|—|`false`|-|

<!-- @vuese:files:props:end -->


## Events

<!-- @vuese:files:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|input|-|-|
|change|-|-|
|uploaded|-|-|
|beforeupload|-|-|

<!-- @vuese:files:events:end -->


