# Markdown

## Hexo的不太完全的入门教程

### 安装Node和git

1. 安装群里的Node和Git
   
### 使用npm安装Hexo，并启动项目

1. 换源

```bash
  npm config set registry https://registry.npm.taobao.org
```

2. 下载hexo-cli脚手架

```bash
  npm install -g hexo-cli
```

3. 创建hexo项目（博客文件夹）
   - 在`目标文件夹`右键，在当前位置打开终端
  ``` bash
  hexo init <filename>
  ```

  __注意：__ 此处需要关闭系统默认安全策略
  ```bash
  set-executionpolicy remotesigned
  ```

4. 运行hexo项目
```bash 
hexo server
```

5. 使用Markdown编写博客

[Mardown教程](https://www.runoob.com/markdown/md-tutorial.html)

6. 上传到GitHub并部署GitPage

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Lycoiref/BlogGuide.git
git push -u origin main
```
