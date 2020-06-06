# doc-fiddler 抓包工具

先clone本项目：

```bash
git clone {git地址}
```

进入到 `doc-fiddler` 文件夹，执行安装依赖包命令：

```bash
npm install
```
```bash
中途若出错可执行  npm install autoconf
```

使用淘宝镜像安装：

```bash
npm install --registry=https://registry.npm.taobao.org
```

依赖安装完成后，运行一下指令，打开电子书：

```bash
npm run dev
```

默认情况会自动打开浏览器；如果没有自动打开浏览器，可以复制 `http://localhost:8666/` ，在浏览器中打开。
