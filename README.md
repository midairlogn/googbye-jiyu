# googbye-jiyu
�����ƽ⼫����ӽ��ҵĹ��߼��ϡ�

## taskkill ɱ������ӽ��ҽ���
*ע��`arcjy.cmd`�����Ͼ�����Щ����*
1.  ���Թ���Ա�������`command ( cmd )`��
2.  ������������ɱ������ӽ��ҽ��̣�
	```
	taskkill /f /im StudentMain.exe /t
	```
3.	��ʹ��PowerShell����������CMD�����������  
	```powershell
	cd C:\Windows\System32\
	.\cmd.exe
	taskkill /f /im StudentMain.exe /t
	```

## �ƽ⼫����ӽ���U������   

1.  ���Թ���Ա�������`command ( cmd )`��
2.  ������������ж��TDFileFilter������
	```
	sc stop TDFileFilter 
	sc delete TDFileFilter #��ѡ
	```
3.	��ʹ��PowerShell����������CMD�����������

	```powershell
	cd C:\Windows\System32\
	.\sc.exe
	stop TDFileFilter
	#���������ѡ
	.\sc.exe
	delete TDFileFilter
	```
 
## ������ӽ��ҳ�������Ա���룺
```
mythware_super_password
```

## ˵����   

ע�⣺`arcjy.cmd`��Ҫ�Թ���Ա������С�

ף�������죡