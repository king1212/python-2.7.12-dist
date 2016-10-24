# python-2.7.12-dist
Binary distribution of Python 2.7.12 + get-pip.py built on CentOS 6

```
sudo yum groupinstall "Development tools"
sudo yum install zlib-devel bzip2-devel openssl-devel ncurses-devel \
                 sqlite-devel readline-devel tk-devel gdbm-devel    \
                 db4-devel libpcap-devel xz-devel
./configure --prefix=/sw/int/eclear/software/python-2.7.12
make
make altinstall
```
