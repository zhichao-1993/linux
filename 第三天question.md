# 第三天
## 1.Linux的文件系统
### 1.1根文件系统
  + root filesystem
  
### 1.2 LSB,FHS(fhs文件系统层级结构标准)
 
  
  1. /boot中是存放什么的目录，包含哪两种东西？
  2. /bin中存放的是什么？
  3. /sbin中存放的是什么?
  4. /lib中存放哪两种文件？
  5. /lib64文件里存放的是什么？
  6. /etc中存放的是什么，都是什么文本？
  7. /home/username是什么？
  8. /root是什么？
  9. /media是什么，比如什么？
  10. /dev中存放什么？
  11. /opt是什么的安装位置？
  12. /srv存放什么数据？
  13. /tmp存放什么？
  



| 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |0 |
  
----



### 1.3 
  
    
  1. /usr存放什么数据？
  2. bin是为了什么而提供的应用程序？
  3. include是什么文件？
  4. share是什么样的数据？
  5. local是什么的安装位置？
  6. /var中存放什么数据文件？
  7. cache是存放什么数据的目录？
  8. lib存放什么数据？
  9. local给什么东西存储可变数据？
  10. lock是什么文件
  11. log存放什么目录及文件？
  12. opt给什么东西存储可变数据？
  13. run存放什么数据？
  14. spool是什么数据池？
  15. tmp存放什么临时数据？
  
| 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |
  
  

---     
  ### 1.3

  1. /proc是用于输出什么的虚拟文件系统
  2. /sys:是用于输出什么的虚拟文件系统
  3. /selinux是什么的存储位置
  
    
| 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |



----  
## 2.Linux上的应用程序的组成部分


1. linux的应用程序由那四种组成？

    
| 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |


---

## 3.Linux下的文件类型
 
 1. -,d,b,c是什么文件类型
 2. l,p,s是什么文件类型
 
 | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |0 |
---

## 4.系统管理类命令
### 4.1关机


1. 关机命令？


 | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |0 |
---
### 4.2重启


1. 重启命令？

 | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |0 |

---
### 4.3用户登录信息查看命令


1. whoami
2. who
3. w

 | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |0 |

----
## 5.bash的基础特性
### 5.1命令历史

    
  1. 命令历史的环境变量HISTSIZE是什么意思？
  2. history # ?
  3. !$ ?
  4. 调用历史中的命令!#,!!,!string是什么意思？
  5. 环境变量HISTCONTROL有什么用？
  6. ignoredups是什么意思？
  7. 如何修改环境变量的值？
  
  
 | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |



----
----
### 5.2命令补全
  + tab键补全

### 5.3路径补全
  + tab键补全
  
### 5.4命令行的展开
  + {}

### 5.5命令的执行结果状态


1. 命令的执行结果状态，成功为什么，失败为什么？
2. $?显示的是什么？

 | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |


---
## 6.目录管理命令

  
  
  1. 如何创建/tmp/x/y1, /tmp/x/y2, /tmp/x/y1/a, /tmp/x/y1/b, /tmp/x/y2/a, /tmp/x/y2/b
  2. 如何创建 x_m,y_m,x_n,y_n
  3. 如何创建/tmp/bin, /tmp/sbin, /tmp/usr, /tmp/usr/bin, /tmp/usr/sbin
  4. 如何递归创建多级目录
  5. 同时创建多个目录
  6. 如何显示目录的结构
  7. 如何删除空目录
  
  
| 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |


---
## 7.文件查看命令



1. 分页显示文件内容的两种方式？
2. 搜索关键字、下一个？
3. 显示文件的前几行
4. 显示文件的后几行

  | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |0 |


---
## 8.文件的时间戳管理工具touch

    
1. 如何查看文件的状态？
2. 文件的三个时间戳？
3. 三个时间戳分别做什么事情？
4. touch的用法
5. touch -a
6. touch -m


  | 当天重复次数 |重复次数(10次)|
| :------:|:------:|
| 0 |1 |

---
## 总结    
1. 文件系统，三大类
2. bash基础特性，5小类
3. 目录管理，2个命令
4. 文件查看，4个命令
5. 时间戳管理，三个时间戳