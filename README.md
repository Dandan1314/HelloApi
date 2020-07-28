# HelloApi

### 简易API服务器，提供一些常用的API服务
项目的目的是将一些常用的功能封装起来，将复杂的操作变成简单的API请求，在使用过程中如果有问题或者更好的意见和建议，可以添加我微信，我邀请你加入技术交流群与我们交流，我会第一时间在群里发布维护、接口更新、添加新接口等通知。

<img width="220" height="220" src="./img/wechat_qun.jpg"/>


项目的[主页地址](https://www.needapi.net/)

**项目的API请求地址 https://i.needapi.net/ ，目前支持HTTP和HTTPS的请求方式**

项目的[申请地址](#)

---

## 目录

- [HelloApi](#helloapi)
    - [简易API服务器，提供一些常用的API服务](#简易api服务器提供一些常用的api服务)
  - [目录](#目录)
  - [**数据返回格式：**](#数据返回格式)
  - [更新记录](#更新记录)
  - [捐赠](#捐赠)
  - [<img width="220" height="300" src="./img/wxPay.png"/>&nbsp;&nbsp;&nbsp;&nbsp;<img width="220" height="300" src="./img/AliPay.png"/>](#img-width220-height300-srcimgwxpaypngimg-width220-height300-srcimgalipaypng)
  - [版权声明](#版权声明)

-----

## **数据返回格式：**

  ```json
  {
      "code": 200000,
      "msg": "请求成功！",
      "data": {}
  }
  ```

- **数据返回格式说明：**

  - **code：** 状态码
  - **msg：** 请求返回的提示信息
  - **data：** 接口返回的内容，详见具体接口信息
  
    | 状态码 | 对应内容                                                    |
    | ------ | ----------------------------------------------------------- |
    | 200000 | 请求成功！                                                  |
    | 403001 | appId或sppSecret校验失败                                    |
    | 404001 | API地址有误或接口正在维护中，可关注微信交流群获取详细通知。 |

------

## 更新记录

**2020-07-29**
- 项目建立，第一个接口为获取IP相关信息

--------

## 捐赠

如果本项目对您有所帮助，可以适当进行捐赠，捐赠金额不限制，全部金额将用于服务器及部分收费接口的维护，同时，如果您有闲置的服务器资源也可以联系我进行捐赠，用于部署相关服务，您的捐赠也是支持我继续维护下去的动力。[捐赠列表](#)

<img width="220" height="300" src="./img/wxPay.png"/>&nbsp;&nbsp;&nbsp;&nbsp;<img width="220" height="300" src="./img/AliPay.png"/>
---------

## 版权声明

本项目为非盈利项目，使用的Api和部分数据来自互联网，如有侵权请联系我删除处理，用户在使用过程中的版权问题由用户自行承担，与项目无关，请知悉！
本站所对外提供的Api接口中，部分数据来源于网络，如有侵权，请联系我进行处理！

-------