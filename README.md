# 欢迎使用ERP进销存V8标准版系统

### 请按照以下方法安装程序

1、首先把目录的 `erpv8.sql` 导入到数据库

2、打开 `application\config\database.php` 文件，找到数据库配置字段

如下：

```php
$db['default']['hostname'] = 'localhost';  //一般默认即可
$db['default']['username'] = 'root';   //数据库用户名
$db['default']['password'] = 'root';  //数据库密码
$db['default']['database'] = 'erpv8';  //数据库名称
```

3、访问您的网址 http://You_IP_or_Domain/

账号为 `admin`  密码为 `admin888`
