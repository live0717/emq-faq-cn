
.. _general:

========
一般问题
========

------------
安装启动问题
------------
Q：emqttd stop 之后，还有一个epmd -daemon进程，如果不杀掉这个进程，直接start，会有问题吗?::

    不会有问题，epmd是Erlang里的Erlang Port Mapper Daemon

Q：windows 启动报错::

    1、检查cmd窗口是不是管理员用户登录；
    2、检查安装目录是否有空格

Q:启动报错原因分析::
    返回错误、/lib64/libc.so.6:version `GLIBC-_2.14` not found (requried by /user/local/emqttd/erts-7.1/bin/escript)
    下载的包和安装操作系统不符


