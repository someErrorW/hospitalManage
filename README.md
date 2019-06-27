# hospitalManage

read me

数据库配置

```
'default': {
    'ENGINE': 'django.db.backends.mysql',
    'NAME': 'hospital_manage_db',  # 数据库名称,需要自己定义
    'USER': 'root',  # 修改为自己的用户名
    'PASSWORD': '123456',  # 管理员密码
    'HOST': '127.0.0.1',  # 修改自己的IP地址
    'PORT': 3306,  # 一般不要修改
}
```



各自的页面和静态文件，放入template和static中对应的文件夹

![](/home/tarena/图片/2019-06-27 20-24-19 的屏幕截图.png)

创建后台管理帐号:

- 后台管理--创建管理员帐号
  - `$ python3 manage.py createsuperuser`            weimz@tedu.cn
  
  - 根据提示完成注册,参考如下:创建后台管理帐号:
  
    - 后台管理--创建管理员帐号
      - `$ python3 manage.py createsuperuser`            
      
      - 根据提示完成注册,参考如下:
      
      - ```
        $ python3 manage.py createsuperuser
        Username (leave blank to use 'tarena'): middleproject  
        Email address: weimz@tedu.cn  # 此处输入邮箱
        Password: # 此处输入密码(密码要复杂些，否则会提示密码太简单)a1b1c1d1
        Password (again): # 再次输入重复密码		a1b1c1d1
        Superuser created successfully.
        $ 
        ```
      
