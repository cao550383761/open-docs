
# 简介
**MapContext.getSkew** 用于获取当前地图的倾斜角。

## 使用限制

- 基础库 [2.6.2](https://opendocs.alipay.com/mini/01iq3i) 或更高版本；支付宝客户端 10.2.0 或更高版本，若版本较低，建议采取 [兼容处理](https://opendocs.alipay.com/mini/framework/compatibility)。
- 此 API 支持个人支付宝小程序、企业支付宝小程序使用。

# 接口调用

## 示例代码

### .js 示例代码
```javascript
// .js
this.mapCtx = my.createMapContext('map');
this.mapCtx.getSkew({
  success: res => {
    console.log(res.skew);
  }
});
```

## 出参
| **属性** | **类型** | **描述** |
| --- | --- | --- |
| skew | Number | 倾斜角。取值范围为 0~60°。 |

