# safari2aria

用 aria2c 来替代你的 safari 默认下载

请搭配mac下的safari进行食用

### 已有功能：
1. 拦截指定后缀文件下载
2. 多aria2c服务支持
3. 右键菜单指定aria2c服务
4. 支持百度云和迅雷离线导出
5. 全局拦截模式


### 快捷键：
功能 | 快捷键
---- | ---
切换默认rpc服务 | option+shift+[123456789]
展示当前默认rpc服务 |  option+shift+`
临时禁用或启用拦截 |  长按cmd并点击链接
全局拦截 |  长按shift并点击链接
设置 |  option+shift+,

### 注意事项
1. aria2已经无需配置SSL证书了
2. 请在aria2c的配置文件中加入如下配置,用以开启百度云和迅雷离线导出时自动更改下载文件名
```
content-disposition-default-utf8=true
```

[下载链接](https://github.com/miniers/safari2aria/releases)

设置：

![image](https://user-images.githubusercontent.com/2039910/27144514-c743a31c-5164-11e7-9f23-4f2a9dcae223.png)

下载：

![image](https://user-images.githubusercontent.com/2039910/27039821-b4518ce6-4fc1-11e7-8dc2-a9b9c1621ae0.png)

#### 迅雷离线导出：
- 开启cookie传递选项
- 选择需要导出的文件
- 如当前为自动拦截模式，长按**shift**并点击**取回本地**按钮即可导出下载至默认rpc服务器
- 如当前关闭了自动拦截默认，需长按**shift+cmd**并点击**取回本地**按钮即可导出下载至默认rpc服务器

#### 百度云分享页导出：
- 关闭cookie传递选项
- 点击下载，打开文件下载窗口
- 如当前为自动拦截模式，长按**shift**并点击**普通下载**按钮即可导出下载至默认rpc服务器
- 如当前关闭了自动拦截默认，需长按**shift+cmd**并点击**普通下载**按钮即可导出下载至默认rpc服务器

