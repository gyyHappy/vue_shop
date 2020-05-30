# Vue shop 开发文档

## git相关

- 创建分支并切换 - git checkout -b '分支名称'
- 查看当前所有的分支 - git branch

## Login模块
### 页面的创建
创建 login.vue 页面
### 相关依赖
在vue-ui中添加开发依赖，less-loader & less 依赖

## axios
### 请求根路径
``
  import axios from 'axios'
  // eslint-disable-next-line no-undef
  axiox.default.baseURL = 'http://localhost:8080/api/private/v1/'
  Vue.prototype.$http = axios
``

## 第三方图标库 - 阿里巴巴Iconfont
- 下载需要的图标到本地，将文件放在assets目录下
- 导入，在mian.js文件中导入./assets/font/iconfont.css
- 使用：在前面加入iconfont + 要是用的图标code 例：prefix-icon="iconfont icon-account"
