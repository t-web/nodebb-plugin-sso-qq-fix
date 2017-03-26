# NodeBB-插件 QQ登入

可以让你通过 QQ账户 登陆/注册 的NodeBB插件

>目前版本存在无法绑定用户的问题(由于腾讯API问题，我们只能新建用户)，这个错误会NodeBB官方回复后修复。

## 安装
```
    npm install nodebb-plugin-sso-qq-fix
```
请在后台中配置您的QQ互联 ID 和 Key.  
> 请把在后台中显示的 Callback URL 填写在QQ互联中。

----
> 该插件参考了：  
> `nodebb-plugin-sso-gihtub`  
> `nodebb-plugin-sso-qq`  
> `nodebb-plugin-sso-qq-new`  