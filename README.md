Buildroot SDK
------

## Initialize repo
### Download  repo

```
git clone https://gerrit.googlesource.com/git-repo
```

## Initialize source code

### 100ask-am335x board

``` bash
$ mkdir -p 100ask_am335x
$ cd 100ask_am335x
$ repo init -u https://github.com/100askTeam/manifests/ -b linux-sdk -m ti335x/100ask-am335x_linux_release_v1.0.xml --no-repo-verify
```
### firefly-rk3288 board

```bash
$ mkdir -p firefly-rk3288
$ cd firefly-rk3288
$ repo init -u https://dev.tencent.com/u/weidongshan/p/manifests/git -b linux-sdk -m rk3288/firefly-rk3288_linux_release.xml --no-repo-verify
```
### roc-rk3399 board

```bash
$ mkdir -p roc-rk3399-pc
$ cd roc-rk3399-pc
$ repo init -u https://dev.tencent.com/u/weidongshan/p/manifests/git -b linux-sdk -m rk3399/roc-rk3399-pc_linux_release.xml --no-repo-verify
```
### 100ask-am437x borad

```bash
$ mkdir -p mini437x
$ cd mini437x
$ repo init -u https://dev.tencent.com/u/weidongshan/p/manifests/git -b linux-sdk -m ti437x/mini437x_linux_release.xml --no-repo-verify
```


## Synchronize all source code

```bash
$ repo sync -j4

Fetching projects: 100% (3/3)
Fetching projects: 100% (3/3), done.
Checking out files: 100% (10246/10246), done.
Checking out files: 100% (56938/56938), done.es:  18% (10547/56938)
Syncing work tree: 100% (3/3), done
```
## Code directory

```
ls -l
```

