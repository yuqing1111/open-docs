# 简介

**my.openCardList** 是打开支付宝卡列表的 API。

有关支付宝卡包详细功能，可查看 [支付宝卡包产品介绍](https://opendocs.alipay.com/open/199/105225)。


## 使用限制

此 API 暂仅支持企业支付宝小程序使用。

# 接口调用

## 示例代码

### .js 示例代码

```javascript
//.js
my.openCardList({
  success: (res) => { 
    console.log('调用成功',res) 
  },
  fail: (error) => {
    console.log('调用失败', error)
  },
  complete:() => {
    console.log('无论调用成功或者失败都会执行')
  }
})
```
### 示例效果图
![avatar](https://img.alicdn.com/imgextra/i2/O1CN01WDgmak1x1vGjkqKHE_!!6000000006384-0-tps-592-1280.jpg)
