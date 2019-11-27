## 关于js-utils-m

[文档地址](https://ifmiss.github.io/js-utils-m/)

#### 产生背景
这是关于个人日常比较通用代码的收集，方便日后使用，编写文档为了以后方便查阅

#### 功能描述
该方法一共包含以下属性，每个属性收集了对应的方法内容

- `dom`
  该属性主要时针对dom元素相关的方法，针对于元素的一些操作

- `store`
  该属性主要是对于数据的操作

- `exp`
  该属性是js-utlis-m里的一个属性，此属性包含对于一些字符，或者元素判断是否符合要求

- `utils`
  其他相关js工具代码

- `device`
  设备相关的检测与方法

## 快速使用
#### 安装
使用npm安装 `js-utils-m` 依赖
```bash
npm i js-utils-m
```

或者直接引用js
```html
<script src="www.daiwei.org/js-utils-m"></script>
<script>
  Dutils.dom.addClass(document.body, 'js-utils-m')
</script>
```

#### 使用
引入`js-utils-m.js`可直接使用其方法
```js
import Dutils from 'js-utils-m'
Dutils.dom.addClass(document.body, 'js-utils-m')
```