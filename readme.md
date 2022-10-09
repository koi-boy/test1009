
#首先将本项目clone到本地:
git clone https://github.com/ShusenTang/Dive-into-DL-PyTorch.git
cd Dive-into-DL-PyTorch


#docker 访问
#之后使用如下命令创建一个名称为「d2dl」的docker镜像：
docker build -t d2dl .

#镜像创建好后，运行如下命令创建一个新的容器：
docker run -dp 3000:3000 d2dl

#最后在浏览器中打开这个地址
http://localhost:3000/#/



#docsify-cli 访问
npm i docsify-cli -g

#然后运行一个本地服务器
docsify serve docs

#这样就可以很方便的在http://localhost:3000实时访问文档网页渲染效果。


#原项目网页版
https://tangshusen.me/Dive-into-DL-PyTorch/#/
