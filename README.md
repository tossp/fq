# fq
翻墙资源
## 资源

github请求代理:
```shell
git config --global http.proxy http://hx.gy:1080
```

Android Studio:
```shell
./android list sdk -u --proxy-host=hx.gy --proxy-port=1080
```
composer镜像:
```json
{
    "repositories": [
        { "packagist": false },
        {
            "type": "composer",
            "url": "http://composer-proxy.jp/proxy/packagist"
        }
    ]
}
```

brew:
```shell
cd /usr/local/
git remote set-url origin http://mirrors.ustc.edu.cn/homebrew.git
brew update
```

### Android SDK在线更新镜像服务器
```
中国科学院开源协会镜像站地址:
    IPV4/IPV6: http://mirrors.opencas.cn 端口：80
    IPV4/IPV6: http://mirrors.opencas.org 端口：80
    IPV4/IPV6: http://mirrors.opencas.ac.cn 端口：80
    
上海GDG镜像服务器地址:  http://sdk.gdgshanghai.com 端口：8000

北京化工大学镜像服务器地址:
    IPv4: http://ubuntu.buct.edu.cn/ 端口：80
    IPv4: http://ubuntu.buct.cn/ 端口：80
    IPv6: http://ubuntu.buct6.edu.cn/ 端口：80
大连东软信息学院镜像服务器地址:
    http://mirrors.neusoft.edu.cn 端口：80
```
