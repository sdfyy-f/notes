## 在pycharm中使用anaconda时，有一些库不可以直接安装，将已经学会安装的库，做笔记，以备使用

#### jieba分词
- 官网https://pypi.org/project/jieba/0.39/#files下载。
- 将下载好后的解压文件放在Anaconda下的 pkgs 目录下。
- 打开cmd窗口，命令activate + 指定环境名（anaconda图形界面可以看到环境名，pycharm也可以），激活相对应的环境
- cd命令切换到**jieba**的目录下，输入python setup.py install回车即可，最后conda list看看是否安装成功。
- 如果如下图所示，恭喜jieba安装成功。
![image](https://user-images.githubusercontent.com/55749682/122873672-a39b8200-d364-11eb-8938-43da23fe5e56.png


#### wordcloud词云库
- wordcloud的版本比较多，要对应好自己的python版本及系统版本
- 官网https://pypi.org/project/wordcloud/#files下载。
- 找对自己合适的安装包下载，python版本可以在cmd中输入python -V查看
- 将下载好的文件放在Anaconda下的 pkgs 目录下
- 打开cmd窗口，命令activate + 指定环境名（anaconda图形界面可以看到环境名，pycharm也可以），激活相对应的环境
- cd命令切换到**pkgs**目录下，输入pip install wordcloud-1.8.1-cp37-cp37m-win_amd64.whl后回车。
- 看反应是否成功安装
