# dev-configs
This repo contains minimal scripts used to initialize new servers for better development efficiency.

## Setup `pip` mirror source
Copy `.pip/` to your home directory.
Or, copy the following lines to your local directory `~/.pip/pip.conf`
```
[global]
index-url = https://pypi.mirrors.ustc.edu.cn/simple/ 
```

## Setup `conda` mirror source
Copy `.condarc` to your home directory. 
Or, copy lines below to your local file `~/.condarc`
```
channels:
  - defaults
show_channel_urls: true
default_channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
```
