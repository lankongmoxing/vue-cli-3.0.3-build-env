# vue-cli

### 从新建项目到设置打包环境
```
1.vue create vue-cli-env
2.新建 vue.config.js 文件，设置baseUrl: './'
3.新建各个环境的文件，例如：.env.development .env.test .env.production
4.在 package.json 中设置打包命令，例如：build:development build:test build:production，在执行命令的语句中设置 mode 环境，例如：--mode test
```

### 关于环境变量的注意事项
```

* 环境名应该与环境文件统一
* 环境文件放置根目录下
* 除了 baseUrl 和 NODE_ENV 其他环境变量使用 VUE_APP 开头
```