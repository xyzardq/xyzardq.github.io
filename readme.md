# xyzardQ的Blog
## 当前域名：
## http://www.xyzardq.com/
## http://xyzardq.github.io/
## http://xyzardq.coding.me/xyzardq/

### 基础进度

#### Hexo
- ~~Hexo配置~~
- ~~Hexo主题~~
- ~~Hexo部署~~

#### Github
- ~~Github配置~~
- ~~SSH Key配置~~
- ~~Blog commit~~

#### 图床
- ~~qiniu配置~~
- ~~qrsync配置~~
- ~~pictures commit~~
- ~~自定义域名~~  

#### 域名
- ~~申请域名~~
- ~~解析域名~~



# Blog管理
## Hexo
### 命令行
<code>hexo new</code>	新建文章（在本机上还会自动用编辑器Atom打开文件）  

<code>hexo generate</code>	搭建网站

<code>hexo deploy</code>    部署网站  

参数 | 描述
----|------
-g | 部署前先搭建  
-m "commit" | 添加commit    

## qiniu

### 命令行
qshell（未使用）
### 图形化
- chrome中的插件qiniu uplaod files  
- qrsbox

## 插件

### 安装插件：

<code>npm install <plugin-name></code>

参数 | 描述
----|------
-S, --save | 自动把模块和版本号添加到dependencies部分
-D, --save-dev | 自动把模块和版本号添加到devdependencies部分
-O, --save-optional | 自动把模块和版本号添加到devdependencies部分
ps:参数一般用```--save```或者不用  
### 启用插件：
在<code>hexo\_config.yml</code>文件添加：
```
plugins:
- <plugin-name>  #插件名
```
### 升级插件：

<code>npm update</code>
### 卸载插件：

<code>npm uninstall <plugin-name></code>

## Github
### 图形化
Github客户端上完成commit和push


## scripts文件夹下脚本功能介绍

### openfile.js:Hexo添加文章时自动打开编辑器
在运行<code>hexo new XXX</code>命令时自动打开编辑器（本机上为Atom）编辑文章


# 版本说明
1.1.0Alpha(现1.0.23Alpha)：

- 转移了qiniu的二级域名
- 添加了置顶功能
- 添加了脚本：Hexo添加文章时自动打开编辑器
- 更改网站语言为简体中文
- 首页文章浏览更改为部分显示
- 添加了新的社交账号
- 个人化多说评论样式
- 添加了404页面
- 添加了分类功能
- 添加了文章目录
- 修复并加强了deploy功能
- 更新了主题，添加了搜索功能
- 添加了rss
- 修复了多说评论系统的一些问题，现在可以在多说后台看到评论了
- 更新了favion和title
- 更换评论系统到disqus
