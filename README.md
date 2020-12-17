# githook 实例

## 简介

+ `git hooks` 可以使用 `php`, `ruby`, `python`, `shell script`, `perl`， `golang` 等语言编写，语言要求很宽泛

+ `git hooks` 是无法随着仓库上传的， 如果您想应用当前实例，请复制相关`hook`到项目下`.git/hooks`里

+ 本项目当前使用`shell script`编写实例，后续将会补全上述语言实例

## 实例

### Client Hooks

#### Committing-Workflow Hooks

+ [ ] `pre-commit`
+ [ ] `prepare-commit-msg`
+ [x] `commit-msg`
+ [ ] `post-commit`

#### Email Workflow Hooks
+ [ ] `applypatch-msg`
+ [ ] `pre-applypatch`
+ [ ] `post-applypatch`

#### Other
+ [ ] `pre-rebase`
+ [ ] `post-rewrite`
+ [ ] `post-checkout`
+ [ ] `post-merge`
+ [ ] `pre-push`
+ [ ] `pre-auto-gc`

### Server Hooks

+ [ ] `pre-receive`
+ [ ] `update`
+ [ ] `post-receive`
