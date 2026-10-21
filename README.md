# 穿梭物语：离线去广告版

《穿梭物语》（ReversEstory）3.03 的离线去广告修改版发布仓库。当前修改版编号为 **v3**，游戏内版本仍显示 3.03。

## 下载

- [下载 v3 APK](https://github.com/Yuanran233/Android-ReversEstory/releases/download/v3.03-offline-v3/ReversEstory-3.03-offline-noads-v3.apk)
- [查看发布页](https://github.com/Yuanran233/Android-ReversEstory/releases/tag/v3.03-offline-v3)
- [完整安装与验收说明](https://github.com/Yuanran233/Android-ReversEstory/releases/download/v3.03-offline-v3/INSTALL-v3.md)
- [SHA-256 校验文件](https://github.com/Yuanran233/Android-ReversEstory/releases/download/v3.03-offline-v3/ReversEstory-3.03-offline-noads-v3.sha256)

APK 支持 ARMv7 和 ARM64，文件大小为 149381084 字节。

## 修改内容

- 关闭广告播放、厂商推广和评分弹窗，停用厂商登录。
- 移除全部声明权限，包括联网权限，供离线游玩。
- 死亡后选择 YES，直接按原有道具代价复活，去除“播放广告”字幕。
- 隐藏命运选择界面的护身宝珠／护身结晶和碎片广告奖励按钮，保留其他区域的正常保存退出。
- 移除结算广告增益选项，将“确定”按钮水平居中。
- 暂停菜单里的便携存档点、传送器在能量不足时不再提供广告选项；能量足够时仍按原费用使用。
- 商店金币不足时显示“金币不足”，保留正常金币购买流程。
- 隐藏“支持开发者／消除广告”入口和相关标识。

没有新增广告奖励、免费道具或付费内容解锁。游戏制作名单和原隐私政策保留。

## 安装与存档

已经安装本项目 v1 或 v2 的手机，直接用 v3 **覆盖安装**。包名、游戏版本号和签名身份保持一致；**不要先卸载或清除应用数据**。

本修改版使用独立签名，无法直接覆盖原厂签名版本。已有原版存档时，先保留原安装与数据；如果安装器提示冲突，不要为安装直接卸载原版。

## 验证范围

已通过 APK 签名、ZIP 完整性、DEX、零权限清单、两套原生架构补丁检查；模拟执行检查覆盖复活扣除与回血、广告控件隐藏、正常存档保留、能量门槛和结算按钮坐标。

Unity 资源包中的 113039 个对象保留原标识、尺寸和偏移，修改仅涉及指定的界面字段。当前没有进行手机端真实渲染或完整关卡实测，实际设备验收步骤见安装说明。

## SHA-256

```text
534d931fe478abd5a3117c24d63ae2ec2dbb832795262cc9bc550f821f30e0f3  ReversEstory-3.03-offline-noads-v3.apk
```
