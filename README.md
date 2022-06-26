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
4. 上传文件
  ```
  !git add
  !git commit -m “这里填写评论（做了哪些修改）”
  !git push    //上传代码到远端    注：在这之前可能需要!git pull，从远端数据库拉代码下来，看看是否有冲突。
  ```
   ![jhhhg](https://github.com/SrcToDes/git_github_application/blob/c4762513d434dd9b0890d98dc4db12d924cc69a9/matlab%E7%89%88%E6%9C%AC%E6%96%87%E4%BB%B6-%E4%B8%8A%E4%BC%A03%E4%B8%AA%E6%AD%A5%E9%AA%A4.png)
