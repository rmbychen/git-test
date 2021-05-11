# git-test
## 配置用户信息
```
// 配置用户名
git config --global user.name 'tubby02'
// 配置邮箱
git config --global user.email 'xxxxxx@163.com'

// 显示config配置
git config --list --global
```
以上```--global```的意思：
-  --global: 对当前所有仓库有效
-  --local: 只对某个仓库有效
-  --system: 对系统所有登录的用户有效

**如果在一个仓库下，同时设值了local和global， local优先**
