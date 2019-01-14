# Android 收款监控程序

用于监控 Android 支付宝与微信的收款通知，需要权限 **通知管理权限**、后续看情况做 **无障碍权限**

> 无障碍每次都要授权，弄到服务器上可能会好一点，再加上自动读取收款记录收款码啥的。

## TODO

- [x] 监控并推送支付宝微信通知内容
- [x] URL [启动](http://app.dxkite.cn/notification-dispatcher/launcher)
- [ ] 开机自启
- [ ] 定时唤醒
- [ ] 收费历史记录
- [ ] 自动读取收费列表

## 原理

监控手机通知，推送消息到服务器  

## URI 启动
- http://app.dxkite.cn/notification-dispatcher/launcher
- dxkite://notification-dispatcher/launcher

## 注意

- 支付宝微信貌似需要日常后台打开接受通知
- 微信可能需要打开语音收款

## 联系我

**dxkite(at)163.com** 

