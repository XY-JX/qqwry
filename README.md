<h2 align="center">qqwry 纯真IP数据库</h2>

### 第一步：composer安装

```
 composer require xy_jx/qqwry
```

### 第二步使用：

#### 根据IP获取获取位置
```
class xy
{      
     var_dump((new xy_jx\qqwry\QQWry)->getLocation('8.8.4.150'));
     
    //array(5) {
    //    ["ip"]=>
    //  string(9) "8.8.4.150"
    //    ["start_ip"]=>
    //  string(7) "8.8.4.5"
    //    ["end_ip"]=>
    //  string(9) "8.8.4.255"
    //    ["region"]=>
    //  string(48) "美国加利福尼亚州圣克拉拉县山景市"
    //    ["asp"]=>
    //  string(12) "谷歌公司"
    //}
}
```