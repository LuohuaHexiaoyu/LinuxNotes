##  查看分区ACL权限是否开启

`dumpe2fs -h 分区目录`

default mount options中是否有acl





## 临时开启分区ACL权限

`mount -o remount.acl/ 根分区`



## 永久开启分区ACL权限

`vi /etc/fstab`

`mount -o remount /`



## 查看ACL命令

` getfacl 文件名`



### 设定ACL权限命令

#### setfacl  [选项] [u:用户名:权限 或  g:用户组:权限 或 m:权限(最大有效权限，只影响ACL和所属组)] [文件名或目录]

`-m [u:用户名:权限 或  g:用户组:权限 或 m:权限(最大有效权限，只影响ACL和所属组)] 设定ACL权限`

`-x [u:用户名 或  g:用户组]删除指定的ACL权限`

`-b 删除所有的ACL权限`

`d: 给目录下新建的文件设定默认ACL权限`

`-k 删除默认ACL权限`

`-R 递归设定ACL权限(对目录下的所有文件或目录都修改)`



### SUID功能



### GUID功能



### SBID功能
