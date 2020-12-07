**该项目基于transmission**

请将部署transmission的服务器与其对应名称写入server.conf中，以`=`作为名称与域名或IP的分隔符,同时请将域名填写完整,不要省略`https`或`http`:

```
example:
google=https://www.google.com
```

运行`install-mtr-control.sh`文件，在引导面板输入`A`用于插入选择框.
如果你修改了transmission页面的位置，请同样修改脚本中的位置.
最后，你将在页面右上角得到一个select下拉框，可供选择你不同的transmission，同时，你需要在所有需要关联的transmission运行该脚本，你可以写好一个`server.conf`后复制到其他主机中便于你完成操作.
如果您有新增的transmission主机,请重新填写`server.conf`,然后先运行`install-mtr-control.sh`,在引导面板输入`R`用于重置transmission,然后重新运行并输入`A`来重新添加.

