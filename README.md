## 24小时无人值守系统

<p align="center">
<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue" alt="license MIT"></a>
<a href="https://github.com/assimon/dujiaoka/releases/tag/2.0.4"><img src="https://img.shields.io/badge/version-2.0.4-red" alt="version 2.0.4"></a>
<a href="https://www.php.net/releases/7_4_0.php"><img src="https://img.shields.io/badge/PHP-7.4-lightgrey" alt="php74"></a>
</p>

## 🔥推荐服务器

- （美国免备案vps，配置2核2G仅需 `20.98$`≈`145RMB`一年/支持支付宝付款）[👉🏻点我直达](https://my.racknerd.com/aff.php?aff=2745&pid=681)

## 界面尝鲜

【官方unicorn模板】
![首页.png](https://i.loli.net/2021/09/14/NZIl6s9RXbHwkmA.png)

【luna模板】
![首页.png](https://i.loli.net/2020/10/24/ElKwJFsQy4a9fZi.png)

【hyper模板】
![首页.png](https://i.loli.net/2021/01/06/nHCSV5PdJIzT6Gy.png)

## 安装篇

- [Linux环境安装](https://github.com/assimon/dujiaoka/wiki/linux_install)
- [Docker安装](https://github.com/assimon/dujiaoka/wiki/docker_install)
- [2.x版本宝塔安装教程](https://github.com/assimon/dujiaoka/wiki/2.x_bt_install)
- [1.x版本宝塔环境安装](https://github.com/assimon/dujiaoka/wiki/1.x_bt_install)
- [常见问题锦集-你遇到的问题大部分能在这里找到解决！！](https://github.com/assimon/dujiaoka/wiki/problems)
- [系统升级](https://github.com/assimon/dujiaoka/wiki/update)
- [各支付对应后台配置](https://github.com/assimon/dujiaoka/wiki/problems#各支付对应配置)
- [视频教程及工具集合](https://pan.dujiaoka.com)

## 支付接口已集成

- [X] 支付宝当面付
- [X] 支付宝PC支付
- [X] 支付宝手机支付
- [X] [payjs微信扫码](http://payjs.cn).
- [X] [Paysapi(支付宝/微信)](https://www.paysapi.com/).
- [X] 码支付(QQ/支付宝/微信)
- [X] 微信企业扫码支付
- [X] [Paypal支付(默认美元)](https://www.paypal.com)
- [X] V免签支付
- [X] 全网易支付支持(通用彩虹版)
- [X] [stripe](https://stripe.com/)

## 基本环境要求

- (PHP + PHPCLI) version = 7.4
- Nginx version >= 1.16
- MYSQL version >= 5.6
- Redis (高性能缓存服务)
- Supervisor (一个python编写的进程管理服务)
- Composer (PHP包管理器)
- Linux (Win下未测试，建议直接Linux)

## PHP环境要求

星号(*)为必须执行的要求，其他为建议内容

- **\*安装 `fileinfo`扩展**
- **\*安装 `redis`扩展**
- **\*终端需支持 `php-cli`，测试 `php -v`(版本必须一致)**
- **\*需要开启的函数：`putenv`，`proc_open`，`pcntl_signal`，`pcntl_alarm`**
- 安装 `opcache`扩展

## 默认后台

- 后台路径 `/admin`
- 默认管理员账号 `admin`
- 默认管理员密码 `admin`

## 免责声明

24小时无人值守系统是免费开源的产品，仅用于学习交流使用！
不可用于任何违反 `中华人民共和国(含台湾省)`或 `使用者所在地区`法律法规的用途。
因为作者即本人仅完成代码的开发和开源活动 `(开源即任何人都可以下载使用)`，从未参与用户的任何运营和盈利活动。
且不知晓用户后续将 `程序源代码`用于何种用途，故用户使用过程中所带来的任何法律责任即由用户自己承担。

## License

24小时无人值守系统 [MIT license](https://opensource.org/licenses/MIT).
