# 清华大学新版网络学堂课程自动下载脚本

## Dependency

python3, bs4, tqdm

```bash
pip3 install bs4 tqdm --user
```

## Usage

```bash
./learn.py [type_number]
```

默认下载本学期课程 （=1），0则为下载所有学期课程

如果不想下载某门课程（比如实验室科研探究），可以在同级目录下新建文件`.ignore`，并添加该课程完整名字，比如：

```bash
➜  wjy git:(master) ✗ cat .ignore 
计算机组成原理
计算机网络安全技术
```

## Features

0. 下载所有课程公告
1. 下载所有课件
2. 下载所有作业文件及其批阅情况
3. 增量更新
4. 可选下载课程
5. 进度条显示下载进度
