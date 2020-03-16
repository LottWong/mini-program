注意正式环境请更换数据地址：

    sqlite ---- mysql
    redis缓存地址请更改

快速安装环境

    pip3 install -r requirements.txt -i https://pypi.doubanio.com/simple/  
 
环境模型初始化

    python3 manage.py migrate
    python3 manage.py makemigrations
    
创建后台超级用户

    python3 manage.py createsuperuser
        user：admin
        password: admin
启动

    python3 manage。py runserver 0.0.0.0:5000

请求后台

    http://127.0.0.1:5000/admin/