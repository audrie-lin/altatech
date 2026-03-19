# Android SDK 整合指南

## 文件結構
![圖]([SDK integration-related documents](https://p9-arcosite.byteimg.com/tos-cn-i-goo7wpa0wc/7e9a02f48a324006988ee048838c816b~tplv-goo7wpa0wc-image.image))

---

## 事件追蹤規劃

### 基本概念

| 概念 | 說明 |
|------|------|
| Event | 使用者行為 |
| User | 使用者屬性 |

---

## SDK 初始化

```java
AppLog.init(this, config);
