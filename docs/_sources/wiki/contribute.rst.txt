##########################
如何参与贡献
##########################

非常欢迎您提交在Kunpeng上运行过的软件， 您可以简单只提交软件名称，也可以是整个运行过程。

整个过程和github项目的开发流程并无差异。如果对github很熟悉，相信您马上就知道要做些什么。


.. note:: 您的贡献对我们非常重要。


1. fork github工程

    浏览器打开工程地址 `RunKunpeng <|runkunpeng_url|>`_ ,点击工程菜单上的fork到自己的项目。clone到本地 ::

        git clone git@github.com:<yourname>/RunKunpeng.git

2. 添加文件到source/apps下

    + 复制source/apps下的随意一个文件进行修改更加方便。
    + 文件以软件的小写名字命名，名字最好和官网地址url中的名字一样
    + 文件使用restructuredText语法编写， 和markdown基本一样，了解 `restructuredText <|restructuredText|>`_

    .. caution:: 如果是商用软件，请从合法渠道获取版权许可。

3. 编译生成html

    ::

        make github

    docs下是目标html。 点击打开docs/index.html查看效果

4. 提交修改上传到github

    ::

        git add software.rst
        git commit
        git push origin master

5. 创建pull request

    在自己的工程上创建pull request， 填写必要信息。 收到pull request之后会审核然后合入

.. |runkunpeng_url| replace:: https://github.com/LyleLee/RunKunpeng
.. |restructuredText| replace:: https://learn-rst.readthedocs.io/zh_CN/
