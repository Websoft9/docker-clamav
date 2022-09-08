# ClamAv



## FAQ

#### ClamAV 容器没有访问宿主机文件的权限?

```
apk add sudo
sudo clamscan -r /scandir
```

#### clamscan 与 clamdscan 有什么区别？

Clamscan 比 Clamdscan 慢，因为必须启动该进程并为传递给它的每个文件重新加载病毒数据库。

#### 扫描显示 Infected files 但没有具体信息？

有待进一步研究
