### UPYUN C# SDK

UPYUN C# SDK，基于 [UPYUN HTTP REST API 接口](http://docs.upyun.com/api/rest_api/) 开发

#### 安装使用

下载后，使用 Visual Studio 直接 Open Project

初始化 UpYun

```
UpYun upyun = new UpYun("bucket", "username", "password");
```

其中，参数 `bucket` 为空间名称，`username` 和 `password` 分别为授权操作员帐号和密码。

启动或 F5 运行


