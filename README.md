# git_github_application
git及github使用
# matlab下版本控制实现
1. 安装git，下载后，在windows环境下安装，安装后，查看是否安装成功，可以在matlab命令窗口输入!git，查看，若成功，会一长串字符出现。
2. github注册个账号
3. 配置git
  - 在cmd窗口，配置用户名和email，这个要和github上注册的保持一致，将来是同步到github的凭证
  ```
   git config global --user.name "你的名字"
   git config global --user.email "你的邮箱地址"
  ```
  配置完后，可以输入以下命令核对下名字和邮箱是否与github上注册的一致:
  ```
  git config user.name
  git config user.email
  或者利用如下命令查看更多的git配置信息：
  git config --list
  ```
4. 上传代码文件到github
  ```
  4.1 通过命令方式
  !git add
  !git commit -m “这里填写评论（做了哪些修改）”
  !git push    //上传代码到远端    注：在这之前可能需要!git pull，从远端数据库拉代码下来，看看是否有冲突。
  ```
 4.2 通过鼠标右键选择的方式。具体就是在matlab文件夹窗口，选定程序文件（如test.m），右键单击-源代码管理,注意：在这之前，需要在matlab选择新建->工程->从git
  - 添加到git
  - 查看并提交更改
  - 刷新git状态
  - 推送
![imagjje](https://github.com/SrcToDes/bulk_files_rename/blob/00f6049979fabe0fc57e7010318973882144b5d7/picture/1.jpg)

## 参考
* [Readme.md语法]（https://www.cnblogs.com/wj-1314/p/8547763.html）
