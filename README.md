# 简介

`DirectoryScanning`是一个超级简单的多线程Web目录扫描工具，融合了御剑、及市面上很多非常强大的字典，使用也非常简单

# 安装

使用Python语言编写

第三方模块用了`requests`,所以`clone`以后只需要安装`requests`模块即可。

```
pip install requests
```

安装完成。

# 使用方法

```
Usage: dirscan.py [options]

Options:
  -h, --help            show this help message and exit
  -u URL, --url=URL     target url for scan
  -f EXT, --file=EXT    target url ext
  -t COUNT, --thread=COUNT
                        scan thread_count
```

# 使用案例
java网站  python DirectScan.py -u  http://127.0.0.1:8088 -f jsp -t 10

php网站   python DirectScan.py -u  http://127.0.0.1:8088 -f php -t 10

asp网站   python DirectScan.py -u  http://127.0.0.1:8088 -f jsp -t 10

![image](https://github.com/github8669/DirctScan/assets/22950238/c523b4dd-bf43-421f-a730-6489aafccd5a)
![image](https://github.com/github8669/DirctScan/assets/22950238/96828750-c251-4f10-863a-aea4c43abf2b)
![image](https://github.com/github8669/DirctScan/assets/22950238/b3d0910a-995f-4178-954d-f9824395f69e)
![image](https://github.com/github8669/DirctScan/assets/22950238/fb3173bf-1453-4cb9-861b-09c2f1e4cd49)


