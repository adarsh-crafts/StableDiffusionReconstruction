setup python
```
sudo dnf groupinstall "Development Tools" -y 
sudo dnf install openssl-devel bzip2-devel libffi-devel zlib-devel readline-devel sqlite-devel xz-devel 
tk-devel -y 
cd /usr/src 
sudo wget https://www.python.org/ftp/python/3.10.13/Python-3.10.13.tgz 
sudo tar -xzf Python-3.10.13.tgz 
sudo ./configure --enable-optimizations 
sudo make altinstall
```