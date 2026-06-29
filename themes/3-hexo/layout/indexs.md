# Why Blog
## Hexo + GitHub Pages 博客搭建部署

### 安装必备软件
1. Node.js：Hexo 运行依赖，官网下载 LTS 长期支持版，安装后终端输入 node -v、npm -v 验证版本。
2. Git：用于代码提交、推送 GitHub。
3. GitHub 账号

框架：[Hexo](https://hexo.io/)

主题：[3-hexo](https://github.com/yelog/hexo-theme-3-hexo)

### 博客目录终端控制台命令  (本地预览地址   http://localhost:4000)

```
hexo new  "我的第一篇文章"	//生成一篇文章
```

```
pwd  //当前所在位置
```

```
hexo clean  //清理旧网页，缓存
```

```
hexo g  //生成
```

```
hexo s  //本地预览
```

```
hexo d  //部署到远端，推送到仓库
```

### 本地博客目录内容保存到Github仓库中后续推送命令  (Lingyi-AI/blog-source)

```
git add .   //作用：把本地所有改动文件「放进暂存区」
```

```
git commit -m "更新说明文字"    //作用：把暂存区的变动打包成一份永久版本快照，保存到本地仓库
```

```
git push    //作用：把本地所有 commit 版本，同步上传到 GitHub 远程仓库
```

## 关于叶落阁
**叶落阁** 是阁主的个人站。

到目前为止已经写了<code class="article_number"></code>篇文章， 共<code class="site_word_count"></code>字。

本站访问人数：<code class="site_uv"></code>人次 ， 访问量：<code class="site_pv"></code>次
