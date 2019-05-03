[![License](https://img.shields.io/badge/license-Apache%202-green.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/xialonghua/kotmvp.svg?branch=master)](https://travis-ci.org/xialonghua/kotmvp) 

# TimerWood
Go 开发的记录 Linux 命令或程序执行时间工具，支持统计各种脚本、Linux命令执行的时间

## prerequisite
需要 root 权限

## Quick Start
## Install
```go
git clone https://github.com/panguangyu/TimerWood.git
mv ./TimerWood /usr/local/timerwood
cd /usr/local/timerwood
ln -s /usr/local/timerwood/main /usr/bin/ti
./install
```

## Usage
```go
> ti "python test/test.py"                            # 计算脚本运行的时间
> ti "python test/test.php"
> ti "ls"                                             # 计算 Linux 命令运行的时间
> ti "mysqldump ..."                                  # 计算 mysql 导出时间
> ti "wget http://..."                                # 计算 wget 下载的时间
```

## Log
```
cat /.Timerwood.dat
```
