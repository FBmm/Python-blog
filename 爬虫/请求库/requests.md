# requests

requests是python实现的最简单易用的HTTP库。

基于urllib，采用Apache2 Licensed开源协议的HTTP库。

相比urllib库，Requests库更加方便，可以节约我们大量的工作，完全满足HTTP测试需求。

## 基本用法

### 安装requests

```py
pip insatll requests
```

注：可能会安装失败，'pip' 不是内部或外部命令解决
> pip.py执行文件在 Scripts 文件夹内
> 环境变量 path 中添加 C:\Python27\Scripts

### 模拟请求

```cmd
# cmd 执行 python 命令
python

# 控制显示 >>> 表示命令执行成功

# 导入 requests
import requests

# 模拟请求
res = requests.get('http://httpbin.org/get')

# 打印请求结果
print(res.text)

# 获取如下结果 表示http请求成功
{
  "args": {},
  "headers": {
    "Accept": "*/*",
    "Accept-Encoding": "gzip, deflate",
    "Host": "httpbin.org",
    "User-Agent": "python-requests/2.22.0"
  },
  "origin": "121.13.218.234, 121.13.218.234",
  "url": "https://httpbin.org/get"
}
```
