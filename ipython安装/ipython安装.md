ipython安装

1.通过 pip 安装(未安装 pip,  可通过 root@lan:/usr/local#  apt install pip  安装)
```
root@lan:/usr/local# curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
root@lan:/usr/local# ./get_pip.py 
root@lan:/usr/local# pip install ipython
```
2.在Git的MINGW64终端里输入： 
```
alias python='winpty python.exe'
```