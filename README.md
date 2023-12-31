# format-json-utils

![npm version](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/bc85b8f40eae4d3cb81194f536a2456d~tplv-k3u1fbpfcp-zoom-1.image)
![license](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/bb9a2953be4945c2ab75ba38c1aad332~tplv-k3u1fbpfcp-zoom-1.image)
![npm bundle size](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3a794536b7c9478e852741bbf395d371~tplv-k3u1fbpfcp-zoom-1.image)

`format-json-utils` 是一个用于在JavaScript中格式化JSON字符串的工具，它基于ES Modules (ESM) 语法实现。支持 Vue2、Vue3、React。。。

## 安装

使用npm安装:

```bash
npm install format-json-utils
```

使用yarn安装:

```bash
yarn add format-json-utils
```

使用示例
以下是一个简单的示例，演示如何在 JavaScript 项目中使用 format-json-utils 来格式化 JSON 数据：

```javascript
import { formatJSON } from 'format-json-utils';

// 场景一
const jsonData = {name: 'John Doe',age: 30,email: 'john@example.com'}; 
// 场景二
// const jsonData = "{\"name\": \"John Doe\", \"age\": \"30\",\"email\": \'john@example.com\'}"; 

const formattedJSON = formatJSON(jsonData);
console.log(formattedJSON);
//{
//    "name":"John Doe",
//    "age":"30",
//    "email":"john@example.com"
//}
```

## API 文档

**formatJSON(jsonObj, errorCallBack): string**

此函数接受一个 JSON 数据对象和一个可选的 error 回调函数，返回格式化后的 JSON 字符串。

## 许可证
本项目基于 MIT 许可证。有关更多信息，请参阅 LICENSE 文件。

## 联系方式
如果您有任何疑问、建议或问题，请在[issues](https://github.com/ghSailing/format-json-utils/issues)留言。