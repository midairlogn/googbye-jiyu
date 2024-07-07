# googbye-jiyu
这是破解极域电子教室的工具集合。

## 破解极域电子教室U盘锁：   

1.  先以管理员身份运行`command ( cmd )`。
2.  输入以下命令卸载TDFileFilter驱动：
	```
	sc stop TDFileFilter 
	sc delete TDFileFilter #可选
	```
3.	或使用PowerShell：（适用于CMD被禁用情况）

```powershell
cd C:\Windows\System32\
.\sc.exe stop TDFileFilter
.\sc.exe delete TDFileFilter #可选
```
 
## 极域电子教室超级管理员密码：
```
mythware_super_password
```

## 说明：   

注意：`arcjy.cmd`需要以管理员身份运行。

祝你玩的愉快！