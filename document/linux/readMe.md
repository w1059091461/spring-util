#### cp -rf 源目录  目的文件夹:
 ```
- f 删除已经存在的目标文件而不提示。
- r 若给出的源文件是一目录文件，此时cp将递归复制该目录下所有的子目录和文件。此时目标文件必须为一个目录名。

 ```
#### 修改文件名:
mv file1 file2
 ```
把当前目录下的file1文件名改成file2，如果该目录下有file2，则覆盖以前的file2文件。
 ```
#### 查看当前防火墙状态:
systemctl status firewalld.service
#### 关闭防火墙:
systemctl stop firewalld.service
