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

