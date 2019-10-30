# lispon.github.io

个人博客, 及博客的源代码.

博客地址: <https://lispon.github.io>

该博客使用 Github Pages 搭建, 使用 sphinx 生成.

## 离线浏览博客

1. 安装 git, 在本地的文件夹右键, `git bash`, 输入 `git clone https://github.com/lispon/lispon.github.io.git`. 会出现新的文件夹 `lispon.github.io`. 不能使用`git clone git@github.com:lispon/lispon.github.io.git`, 因为你的**ssh key**不在我的列表内, 所以无法连接.

2. 使用浏览器打开该文件夹中的 `index.html`, 与 <https://lispon.github.io> 效果相同.

## 注意

1. html 文件的源码在 `lispon.github.io/docsrc` 路径下, 如果不要rst源码, 可以删除`docsrc`文件夹.

2. 如果需要手动生成 html, 需要安装好 sphinx 环境, 那么可以只保留 docsrc 文件夹, 打开 cmd 窗口, 进入到 docsrc 文件所在的路径, 输入 `make github`, 会自动在 docsrc 所在路径的上一层目录生成完整的 html 文件及附属的 css 等等文件及文件夹; 也可以使用 `make html`, 在 docsrc 文件夹下的 `_build/html` 路径下, 生成完整的 html 文件.

3. 当博客更新时, 本地不会得到通知, 需要再次执行`git pull`, 如果已经全部更新, 则会显示`Already up to date`.
