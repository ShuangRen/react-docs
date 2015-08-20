# React文档和网站

我们使用[Jekyll](http://jekyllrb.com/)来构建这个网站，该网站（[绝大部分](http://zpao.com/posts/adding-line-highlights-to-markdown-code-fences/)）使用Markdown。

## 安装

如果你要在此网站上做修改，你将会想安装运行一个本地版本。

### 依赖

为了使用Jekyll，你需要先安装Ruby。

 - [Ruby](http://www.ruby-lang.org/) (version >= 1.8.7)
 - [RubyGems](http://rubygems.org/) (version >= 1.3.7)
 - [Bundler](http://gembundler.com/)

Mac OS X预装了Ruby，但是你可能需要更新RubyGems（通过`gem update --system`命令）。另外，[RVM](https://rvm.io/)和[rbenv](https://github.com/sstephenson/rbenv)也是安装Ruby的流行方式。

> 注意:
>
> 由于Rubygems官方网站有时候有问题，也许你需要使用[国内镜像](http://www.oschina.net/news/24321/rubygems-taobao-mirror)安装

一旦你拥有了RubyGems，并且安装了Bundler(通过`gem install bundler`命令)。

可以学习[Jekyll](http://jekyllrb.com/) 或 以下命令来完成Jekyll的安装

```sh
$ gem install jekyll
```

### 启动

使用Jekyll来启动本地网站（默认地址是`http://localhost:4000`）：

```sh
$ bundle exec rake
$ bundle exec jekyll serve -w
$ open http://localhost:4000/react/
```