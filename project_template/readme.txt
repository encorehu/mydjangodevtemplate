windows下把
project_name.prj # ultraedit的项目文件, 17.0以后的版本
dos.cmd # 直接进入dos.cmd 所在的目录运行dos命令行
db.cmd  # 同步新建立的app的models
run.cmd # 运行django develop webserver在http://localhost:8000/

这几个文件放到 C:\Python27\Lib\site-packages\django\conf\project_template 目录下

以后使用django-admin.py 创建django项目时就可以直接拥有上面这几个文件了