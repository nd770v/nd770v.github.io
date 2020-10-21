python pip install指定国内源镜像
　　有时候安装一些依赖包，网不好，直接超时，或者这个包就是死都下不下来的时候，可以指定国内源镜像。

　　pip install -i 国内镜像地址 包名

　　e.g. pip install -i  http://mirrors.aliyun.com/pypi/simple/ numpy 这是临时指定镜像地址

清华：https://pypi.tuna.tsinghua.edu.cn/simple

阿里云：http://mirrors.aliyun.com/pypi/simple/

中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/

华中理工大学：http://pypi.hustunique.com/

山东理工大学：http://pypi.sdutlinux.org/ 

豆瓣：http://pypi.douban.com/simple/

note：新版ubuntu要求使用https源，要注意。


Jupyter Notebook是一个非常赞的可用于教学，探索和编程的环境，但最原始的Jupyter Notebook是缺乏一些强功能的。但幸运的是，有很多方法可以改进这个工具，比如：Jupyter Notebook的扩展。



▍快速安装



在命令提示符中运行以下命令：



pip install jupyter_contrib_nbextensions &&
jupyter contrib nbextension install 


