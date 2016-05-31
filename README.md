项目介绍
====

[Gulp:前端构建利器](http://gulpjs.com/) ( [gulp中文网](http://www.gulpjs.com.cn/))，可以很好地用自动化构造工具增强我们的前端开发流程。

这个项目是自己写的一套 [gulp模板](https://github.com/cody1991/gulp-template)。

gulp.js的核心部分在gulpfile.js配置文件,可以在 [这里](https://github.com/cody1991/gulp-study/blob/dev/gulpfile.js) 查看文件代码。

gulp是基于node.js的，在gulpfile.js开头部分我们引入了N个模块。主要是 [gulp](https://github.com/gulpjs/gulp) 本身，检测js代码是否规范的 [jshint](https://github.com/spalger/gulp-jshint) 模块,压缩js文件的 [uglify](https://github.com/terinjokes/gulp-uglify) 模块,CSS预处理语言的 [Less](https://github.com/plus3network/gulp-less) 模块,CSS浏览器兼容前缀自动补充的 [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) 模块,压缩CSS文件的 [gulp-clean-css](https://www.npmjs.com/package/gulp-clean-css) 模块,文件的合并 [concat](https://github.com/wearefractal/gulp-concat) 模块，以及文件的重命名 [rename](https://github.com/hparra/gulp-rename) 模块，构建本地服务器并带有刷新功能的 [browser-sync](https://www.npmjs.com/package/browser-sync)模块，让gulp任务能够按照顺序执行的[run-sequence](https://www.npmjs.com/package/run-sequence) 模块。

另外在这里提一下 [HTML5 Boilerplate](http://www.bootcss.com/p/html5boilerplate/) ，在这个网站下可以看到这样的介绍：“HTML5 Boilerplate帮你构建快速，健壮，并且适应力强 的web app或网站。这个小小的源码包集合了100位开发者的经验，你可以将这些经验运用在你的项目中。”更多的细节可以自己看看。我给出的本gulp模板基本结构也是基于HTML5 Boilerplate的。可以在我的 [mylib](https://github.com/cody1991/mylib/tree/gh-pages/framwork/signlepage-lib-flexible) 项目中使用了淘宝的[lib-flexible](https://github.com/amfe/lib-flexible)。


项目使用
===

1   下载本项目
---

    git clone https://github.com/cody1991/gulp-template.git

or
    
    npm install cody-gulp-template


2   下载依赖插件，执行gulp命令
---
    
    cd 对应目录
    npm install
    gulp
