# 简介

## models

存放数据库的模板

## 变量命名规范

model: Aaaaa_aaaaa
app: KBMS(kitboard mange system)

## TODO

* [ ] 完成所有模型的建立

##
[数据库问题看这](https://www.cnblogs.com/aaron-agu/p/8985055.html)


>创建网站管理员

运行`python manage.py createsuperuser`

> 迁移是非常强大的功能，它能让你在开发过程中持续的改变数据库结构而不需要重新删除和创建表 - 它专注于使数据库平滑升级而不会丢失数据。我们会在后面的教程中更加深入的学习这部分内容，现在，你只需要记住，改变模型需要这三步：

1.编辑 models.py 文件，改变模型。
2.运行 `python manage.py makemigrations` 为模型的改变生成迁移文件。
3.运行 `python manage.py migrate` 来应用数据库迁移。