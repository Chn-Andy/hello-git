## Hello git

**推送项目到`github`上的步骤如下**

1. 在`github`上创建一个`repostory`(资料库,对于项目来说也可以做为项目目录)

2. 在本地执行`git remote add origin git@github.com:Chn-Andy/hello-git.git`命令,它的意思是添加一个远程地址,然后用`origin`来表示`git@github.com:Chn-Andy/hello-git.git`这个远程地址

3. 然后执行`git push -u origin master`命令,它的意思是对送当前分支数据到远程的`master`,注意这个时候`origin`就表示的是上面那个`git`地址`git@github.com:Chn-Andy/hello-git.git`

4. 这个时候在`github`上就能看到这个`master`分支的数据了,和本地的是一样的

