Buildroot SDK
------

# Initialize repo
## Download  repo

```
git clone https://gerrit.googlesource.com/git-repo
```

# Initialize source code

## 100ask-am335x board
Get the source code
```
$ mkdir -p 100ask_am335x
$ cd 100ask_am335x
$ repo init -u https://github.com/100askTeam/manifests/ -b linux-sdk -m ti335x/100ask-am335x_linux_release_v1.0.xml --no-repo-verify
```

## 100ask-am437x borad
Get the source code
```
$ mkdir -p mini437x
$ cd mini437x
$ repo init -u https://dev.tencent.com/u/weidongshan/p/manifests/git -b linux-sdk -m ti437x/mini437x_linux_release.xml --no-repo-verify
```
## firefly-rk3288开发板
获取源码
```
$ mkdir -p firefly-rk3288
$ cd firefly-rk3288
$ repo init -u https://dev.tencent.com/u/weidongshan/p/manifests/git -b linux-sdk -m rk3288/firefly-rk3288_linux_release.xml --no-repo-verify
```
## roc-rk3399开发板
获取源码
```
$ mkdir -p roc-rk3399
$ cd roc-rk3399
$ repo init -u https://dev.tencent.com/u/weidongshan/p/manifests/git -b linux-sdk -m rk3399/roc-rk3399_linux_release.xml --no-repo-verify
```


# 同步代码repo sync

```
$ repo sync -j4

```
```
Fetching projects: 100% (3/3)
Fetching projects: 100% (3/3), done.
Checking out files: 100% (10246/10246), done.
Checking out files: 100% (56938/56938), done.es:  18% (10547/56938)
Syncing work tree: 100% (3/3), done
```
# 代码目录
查看下载好的源码目录
```
ls -l
```

