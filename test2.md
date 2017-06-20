# centos 安装node.js

### 系统预置条件

* `gcc` and `g++` 4.9.4 or newer
* Python 2.6 or 2.7
* GNU Make 3.81 or newer

### 查看及配置

##### 查看发行版本

```shell
cat /etc/redhat-release
```

##### 查看gcc g++

```console
rpm -q gcc rpm -q gcc-c++
```

##### 安装gcc g++

```console
yum -y install gcc gcc-c++ kernel-devel
```

##### 查看python
```console
python -V
```

### node.js包下载及安装

当前发行版本及长期维护版本可在官网<https://nodejs.org/download/release/>获得，长期维护版本的命名规则如：latest-_codename_, 比如[latest-argon](https://nodejs.org/download/release/latest-argon/)
