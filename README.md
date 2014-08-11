jquery_update: to 1.7
http://drupalcode.org/project/jquery_update.git/snapshot/baff5d15a438cfa8216997e067518f3c1a28bd5e.tar.gz




为微信服务配置love2in1数据库

在sites/default/settings.php文件里添加以下代码
   $databases['love2in1']['default'] = array(
    'driver' => 'mysql',
    'database' => 'love2in1',
    'username' => 'love2in1',
    'password' => 'password',
     'host' => 'localhost',
     'prefix' => '',
   );



love2in1 服务号 菜单设置地址 http://new.love2in1.com/?q=admin/structure/menu/manage/wechat 
微信服务号API设置地址 http://new.love2in1.com/?q=admin/config/wechat
