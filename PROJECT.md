---
team: 醒伴测试队
solution: 语音强提醒药盒（测试）
status: 原型开发中
demo: https://modelscope.cn/studios/khub-openrd/wake-mate-demo（示例）
---

# WakeMate · 发作性睡病语音强提醒药盒

## 项目背景与解决的问题
（测试项目）针对发作性睡病"白天秒睡听不到闹钟、醒来记忆断片怕重复服药"的痛点，
做强震动+语音双重提醒、开合自动记录、间隔锁定的智能药盒。

## 主要功能
- 强震动 + 语音双通道提醒，持续到实际取药
- 盒体屏幕常显"上次服药时间"，未到安全间隔物理锁定
- 家属端推送

## 技术方案
ESP32 + 震动马达 + OLED + 微信小程序；详见 docs/。

## 团队成员
- 张三（嵌入式）- 李四（小程序）- 王五（病友代表）

## 魔搭 Demo
https://modelscope.cn/studios/khub-openrd/wake-mate-demo（示例）

## 运行说明
见 docs/run.md（测试占位）。
