# vue-cesium-start

一个基于Vue2.x的简易Cesium开发模板

## 效果

![demo](/readme_images/demo.png)

## 项目初始化

```
npm install
```
### 配置
注：以下配置非必须，根据实际情况选择。

补全`src/common/js/config.js`中的`Token`信息（Cesium Ion Token和天地图Token）：

- `CesiumIonDefaultAccessToken`：前往 https://cesium.com/ 中注册账号，[详细教程](https://syzdev.cn/2021/08/10/%E6%B3%A8%E5%86%8CCesium%20ion%E6%95%99%E7%A8%8B/)，并且创建`Token`；
- `TianDiTuToken`：前往 https://uums.tianditu.gov.cn/register 中注册账号，[详细教程](https://syzdev.cn/2021/08/11/注册天地图Token教程/)，并且创建`Token`。

### 编译

```
npm run serve
```

### 打包
```
npm run build
```

