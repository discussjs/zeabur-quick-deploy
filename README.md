
## 部署

1. [fork](https://github.com/discussjs/zeabur-quick-deploy/fork) 本仓库
2. 在 [zeabur](https://zeabur.com) 中引入你 fork 的仓库
3. 在 [zeabur](https://zeabur.com) 中创建数据库服务(例如 mongodb)，它会提供一个数据库连接的 url
4. 在 [discuss](https://discuss.js.org/guide/More-DataBase.html) 官网，根据自己使用的数据库设置对应的环境变量，注意不要漏掉 `DISCUSS_DB_TYPE` 环境变量