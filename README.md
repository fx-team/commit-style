# commit-style

## 目的
- 统一团队Git commit日志标准，便于后续代码review，版本发布以及日志自动化生成等等。
- 统一团队的Git工作流，包括分支使用、tag规范、issue等

## Git commit日志基本规范
```git
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

### 对格式的说明如下：
type代表某次提交的类型，比如是修复一个bug还是增加一个新的feature。所有的type类型如下：
feat： 新增feature
fix: 修复bug
docs: 仅仅修改了文档，比如README, CHANGELOG, CONTRIBUTE等等
style: 仅仅修改了空格、格式缩进、都好等等，不改变代码逻辑
refactor: 代码重构，没有加新功能或者修复bug
perf: 优化相关，比如提升性能、体验
test: 测试用例，包括单元测试、集成测试等
chore: 改变构建流程、或者增加依赖库、工具等
revert: 回滚到上一个版本

### 格式要求：
```
# 标题行：50个字符以内，描述主要变更内容
#
# 主体内容：更详细的说明文本，建议72个字符以内。 需要描述的信息包括:
#
# * 为什么这个变更是必须的? 它可能是用来修复一个bug，增加一个feature，提升性能、可靠性、稳定性等等
# * 他如何解决这个问题? 具体描述解决问题的步骤
# * 是否存在副作用、风险? 
#
# 尾部：如果需要的化可以添加一个链接到issue地址或者其它文档，或者关闭某个issue。
```

## 参考资料
[Git commit message和工作流规范](https://ivweb.io/topic/58ba702bdb35a9135d42f83d)

[git-commit-style-guide](https://github.com/iv-web/git-commit-style-guide)

[angular](https://github.com/angular/angular/commits/master)
