# -Windows多版本python中pip问题，为了使用方便，会将python中pip改成对应的pip2,pip3
python改成对应版本的python2，python3，但此时在cmd中pip会出现Fatal error in launcher: Unable to create process using '"'
此时，将在python文件中再添加一个python名字的exe，就OK了


# -windows10 安装jupyter   (python3.5)
 File "c:\python35\lib\site-packages\tornado\util.py", line 21, in <module>
    from typing import (
ImportError: cannot import name 'Type'
  
  tornado版本问题，使用pip3默认下载了6.0.2 ，删除该版本，重新下载tornado5，会下载对应python35对应的版本。
  
  
# -Linux16.04中配置LSD-SLAM时，
