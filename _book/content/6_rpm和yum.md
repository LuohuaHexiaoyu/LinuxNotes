# RPM包

### rpm安装与卸载

`-i(nstall)`

`-U(pgrade)升级`

`-e(rase)卸载`

`-v(erbose)显示详细信息`

`-h(ash)显示进度`

`--nodeps不检测依赖性，不推荐使用`

`-ivh安装使用`

`-Uvh升级使用`

`-ivh安装使用`

### rpm查询

`-q(uery)`

`-a(ll)`

`-f(ile)查询系统文件属于哪个软件包`

`-R(equire)查询依赖`

`l(ist)`

`-qi已安装包的详细信息`

`-qip未安装包的详细信息`

### rpm校验（是否更改）

`-V`

`S文件大小是否改变`

<p>M文件类型或权限（rwx）是否改变</p>

<p>5文件内容是否改变</p>

<p>T文件修改时间是否改变</p>

<p>c配置文件</p>

<p>d普通文件</p>

<p>g不应该出现的文件</p>

<p>l授权文件</p>

<p>r描述文件</p>

### rpm包中文件提取（用于从包中提取某一个文件对系统进行修复）

`rpm2cpio rpm包文件|cpio -idv 目标路径`

## yum(网络源)

`list`

`search`

`-y(自动执行安装) install`

`-y(自动执行安装) update(不推荐使用)`

`grouplist [软件包组] 软件包组安装`

`groupremove [软件包组] 软件包组删除`

### yum(光盘源)

1. 挂载光盘
2. 通过改名让网络源失效
3. 修改本地yum源文件（CentOS_Media.repo) 



