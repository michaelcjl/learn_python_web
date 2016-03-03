安装 Flask 最便捷的方式是使用虚拟环境
虚拟环境使用第三方实用工具 virtualenv 创建。输入以下命令可以检查系统是否安装了
virtualenv ：
$ virtualenv --version

大多数 Linux 发行版都提供了 virtualenv 包。例如，Ubuntu 用户可以使用下述命令安
装它：
$ sudo apt-get install python-virtualenv
现在你要新建一个文件夹flasky，用来保存示例代码
下一步是使用 virtualenv 命令在 flasky 文件夹中创建 Python 虚拟环境。这个命令只有一
个必需的参数，即虚拟环境的名字
一般虚拟环境会被命名为 venv ：
$ virtualenv venv
现在，flasky 文件夹中就有了一个名为 venv 的子文件夹，它保存一个全新的虚拟环境，其
中有一个私有的 Python 解释器。
可以通过下面的命令激活这个虚拟环境：
$ source venv/bin/activate

执行下述命令可在虚拟环境中安装 Flask：
(venv) $ pip install flask

安装flask扩增包
pip install flask-bootstrap
pip install flask-script
pip install flask-moment
pip install flask-wtf
pip install flask-sqlalchemy



