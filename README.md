# CentOS-sources
:x::x::x: CentOS Linux 7 reached end of life (EOL) on June 30, 2024.

This repository provides a list of still-available CentOS 7 software repositories. (Mostly for chinese users)

## Mirror Lists

### Todo

- :star: [Aliyun](https://developer.aliyun.com/mirror/)
  - :arrow_right: CentOS 7
    - :white_check_mark: CentOS Base
    - :white_check_mark: CentOS-SCLo-scl
    - :white_check_mark: CentOS-SCLo-scl-rh
    - :white_check_mark: epel(RHEL 7)
    - :white_check_mark: RPM Fusion
    - :white_check_mark: CUDA

## Usage

- (Recommended) backup old files in /etc/yum.repos.d/ 

```shell
git clone https://github.com/weimeng23/CentOS-sources
cd CentOS-sources
cp aliyun_centos7/* /etc/yum.repos.d/
yum clean all
yum makecache
yum repolist
```
