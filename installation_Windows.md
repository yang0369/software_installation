# install WSL 

## open powershell admin, 

check available distro: 
```
wsl --list --online
```


# install anaconda on WSL


```
# check conda version
https://repo.continuum.io/archive
# download 
wget https://repo.continuum.io/archive/Anaconda3-5.3.1-Linux-x86_64.sh
# install
bash Anaconda3-5.3.1-Linux-x86_64.sh
```

# set default directory for wsl:
```
echo "cd /mnt/d" >> ~/.bashrc
```