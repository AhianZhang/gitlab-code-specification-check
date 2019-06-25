# 目的
- 规范代码

- 方便 code-review

# 为什么使用 server hooks

- 具有强制性

- 灵活

# 如何使用

pre-receive 的默认位置在  ``/opt/gitlab/embedded/service/gitlab-shell/hooks`` 下，具体的可以查看 gitlab 的配置。

将 gitlab 中的 pre-receive 替换成本仓库中的 pre-receice，修改其中的 JAVA 位置和 p3c jar包的位置，以及用'【】'括起来的提示语，其他的不需要动

# 功能

- [x] git commit message 规范检测

- [x] code 规范检测

- [ ] js 规范（可以使用 eslint 自己改一下脚本）

# 参考
[阮一峰 git commit message 介绍](https://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)

[PMD包配合GitLab提升团队代码质量](https://www.jianshu.com/p/b87ca8615c9c)
