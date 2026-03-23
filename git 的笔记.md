# gitbook
git config --global http.sslBackend schannel 告诉git 去使用系统自带的整数库
1
touch 文件名.文件类型 （创建一个空文件）
2
echo"要写入的内容“文件名.文件类型  （创建一个带有初始内容的文件）
3
mkdir 文件名 （创建一个空的文件夹）
4
cd /d 进入D盘
cd project 进入磁盘内的文件夹
5
git config --global user.name "keqing" （设置git 的全局用户名）
6
git config --global user.email "gu_mingze@qq.com" "设置git的全局邮箱"
7
ssh-keygen -t rsa -b 4096 -C "gu_mingze@qq.com" 生成一对密钥
cat ~/.ssh/id_rsa.pub 查看密钥
8
git add . （将文件做过的修改放到暂缓区）
git commit -am "备注"  （将暂缓区的内容记录下来） 
git push  将本地仓库的项目上传到远程服务器上 （将本地项目与远程仓库关联）
git remote add remotename 远程仓库的URL  （将git 与远程仓库关联起来）
git remote -v （查看git 关联的远程仓库）
git remote rm origin （删除现在git关联的远程仓库）
rm -rf 文件名  （删掉文件）

