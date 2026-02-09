Iamx一个博客框架，超轻量级个人博客模板。完全基于 Github PagesGithub 和 IssuesGithub Actions 。不需要本地部署，从搭建到写作，只需要18秒，2步搭建好博客，第3步就是写作。

安装
1.【创建仓库】点击通过模板创建仓库，建议仓库名称为，其中为你的github用户名。XXX.github.ioXXX

2.【启用Pages】在仓库的中下面选择。SettingsPages->Build and deployment->SourceGithub Actions

3.【开始写作】打开一篇issue，开始写作，并且必须添加一个（至少添加一个），再保存issue后会自动创建博客内容，片刻后可通过https://xxx.github.io/ 访问（可进入Actions页面查看构建进度）。标签Label

4.【手动全局生成】这个步骤只有在修改文件或者出现奇怪问题的时候，需要执行。config.json

通过Actions->build Gmeek->Run workflow->里面的按钮全局重新生成一次
在本仓库提交Issues之前，请手动全局生成一次。如果还有错误，提交后，我会帮忙查看构建流程，定位问题出处。

特性
UI界面和Github同源，只引入了Github原生CSS：primer.style
博客写作在Issues中完成后，自动触发Actions执行部署任务
评论系统引入utteranc.es
使用对html进行渲染，可通过模板自定义UI主题jinja2
