# login

登录窗体

## Props

<!-- @vuese:login:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|types|类型|`Array`|`false`|['mc']|
|qronly|只显示QR|—|`false`|true|
|inwx|是否维系环境|—|`false`|false|
|inding|是否钉钉环境|—|`false`|false|
|loginapi|登录API|—|`false`|/member/signin|
|vcodeapi|验证码API|—|`false`|/member/sendcode|
|wxauthapi|获取微信Oauth网址的API|—|`false`|/member/wxauthurl|
|dingauthapi|钉钉登录API|—|`false`|/member/dingauthurl|
|authkeyapi|二维码登录获取key的API|—|`false`|/member/authkey|
|qrurl|二维码URL|—|`false`|document.location.origin + '/app/weblogin'|
|autologin|是否自动登录|—|`false`|true|
|loginext|扩展餐素|—|`false`|-|
|canreg|是否注册|—|`false`|false|
|usertext|用户名文本|—|`false`|手机号|
|userplaceholder|用户名说明|—|`false`|您的手机号码|
|binding|是否绑定模式（禁用自动登录）|—|`false`|false|
|title|标题|—|`false`|系统登录|

<!-- @vuese:login:props:end -->


## Events

<!-- @vuese:login:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|destroy|-|-|
|register|-|-|
|fail|-|-|
|success|-|-|

<!-- @vuese:login:events:end -->


