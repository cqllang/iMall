

# Routes.php


app/Http/routes.php

连起来就是 admin/wechat/info


对应的就是WechatInfoController

resource（）就是增删改查那些都在这个控制器里面


git update-index --assume-unchanged config/wechat.php //忽略已跟踪文件的改动

composer install // 安装信赖到vendor

需要artisan 文件
php artisan list
php artisan key:generate  //生成key 在.env
php artisan migrate //执行所有未执行的迁移 Run the database migrations