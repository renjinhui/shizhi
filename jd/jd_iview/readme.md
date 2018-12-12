## 解压到本地
## 在对应的文件夹下运行cmd命令
## 在对应的dos命令窗口 执行  cnpm i 或 npm i
## 上个命令执行完毕之后  运行  npm run dev


##  工程化搭建项目 步骤
1、使用iview 脚手架 或者 vue-cli脚手架搭建项目
2、搭建完成后，进入相应文件；执行cmd；  敲命令 cnpm i 或着 npm i 或者 yarn 后；敲回车
3、等所有的依赖包安装完成后；我们 在运行dos命令： npm run dev 把项目起来
4、等项目编写完成之后； 我们运行 npm run build 进行代码打包


把 远程的css文件内容赋值下来  粘贴到 index.css 中；
把 template 中的 index.ejs 中的link(远程的css)删除
然后再重新 run build 
再去把dist 和  index_prod.html 放到 桌面的对应文件夹中
再执行  git add .
git commit -m '备注'
git push 