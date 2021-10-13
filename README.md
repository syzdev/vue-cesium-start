# vue-cesium-start

一个基于Vue的简易Cesium开发模板

## 效果

![demo](/pulic/demo.png)

## 项目初始化

```
npm install
```

补全`src/common/js/config.js`中的`Token`信息（Cesium Ion Token和天地图Token）：

- `CesiumIonDefaultAccessToken`：前往 https://cesium.com/ 中注册账号，[详细教程](https://syzdev.cn/2021/08/10/注册Cesium ion教程/)，并且创建`Token`；
- `TianDiTuToken`：前往 https://uums.tianditu.gov.cn/register 中注册账号，[详细教程](https://syzdev.cn/2021/08/11/注册天地图Token教程/)，并且创建`Token`。

### 编译

```
npm run serve
```

### 打包
```
npm run build
```

