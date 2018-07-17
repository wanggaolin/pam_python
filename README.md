# pam_python
## update time:2018-07-17 03:48:23
## download page:https://sourceforge.net/p/pam-python/code/ci/default/tree/


### 安装方法1
cd /usr/local/src ; git cloen git@github.com:wanggaolin/pam_python.git
cd pam_python && make lib
 
### 安装方法2
yum -y install pam pam-devel gcc-c++
yum install python-devel
cd /usr/local/src ; wget https://sourceforge.net/code-snapshots/hg/p/pa/pam-python/code/pam-python-code-19f932b71918cbcd639a26bef79e2de0c3d9d5c4.zip
unzip pam-python-code-19f932b71918cbcd639a26bef79e2de0c3d9d5c4.zip
cd pam-python-code-19f932b71918cbcd639a26bef79e2de0c3d9d5c4
make lib



