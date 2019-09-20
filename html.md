## html 部分 笔记整理

-   你想把哪个文件夹 上传到 github 仓库 ,就打开这个文件夹,然后 右键 git bash here

-   四个区域

    -   本地仓库 git init 初始化本地仓库
    -   暂存区 git add

-   上传笔记 (第一次)

    -   新建一个 github 仓库
    -   找到对应的保存笔记的文件夹 执行 git init
    -   添加笔记或者修改笔记
    -   git add . 把文件夹内的所有 文件 添加到 暂存区
    -   git commit -m'提示信息' 把暂存区的内容 提交到 git 本地仓库
    -   本地仓库和 远程仓库 建立联系 git remote add origin 仓库地址
    -   git push origin master 同步到远程仓库

-   修改
    -   git add .
    -   git commit -m'修改了文件'
    -   git push origin master
