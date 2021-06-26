# a repository to learn lerna

## 命令
### 创建
```
lerna create @alan/utils
lerna create @alan/projecta
lerna create @alan/projecta
```
### 增加依赖模块
```
yarn add react // 所有package都会加上
lerna add dayjs --scope @alan/utils // 为utils加上dayjs
lerna add @alan/utils --scope @alan/projecta // 为projecta加上utils
```