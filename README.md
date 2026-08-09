# 小熊天气 · 安装包下载

「小熊天气」Android App 的安装包发布仓库（仅包含 APK，不含源代码）。

## 最新版本

> 推荐前往 **GitHub Releases** 页面下载最新安装包：
> https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/latest

| 版本 | 文件 | 大小 |
|------|------|------|
| 1.5.1 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.5.1/app-full-release.apk) | 约 12 MB |
| 1.5.0 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.5.0/app-full-release.apk) | 约 12 MB |
| 1.4.9 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.4.9/app-full-release.apk) | 约 12 MB |
| 1.4.8 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.4.8/app-full-release.apk) | 约 12 MB |
| 1.4.7 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.4.7/app-full-release.apk) | 约 12 MB |
| 1.4.5 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.4.5/app-full-release.apk) | 约 12 MB |
| 1.4.4 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.4.4/app-full-release.apk) | 约 12 MB |
| 1.4.3 | [app-full-release.apk](https://github.com/zhangruyangm-creator/xiaoxiong-weather-releases/releases/download/v1.4.3/app-full-release.apk) | 约 12 MB |

## 版本更新记录

| 版本 | 日期 | 主要更新 |
|------|------|----------|
| 1.5.1 | 2026-08-09 | 修复温度符号：全 App 统一为国标/SI 的 °C / °F 写法（此前摄氏度用了预组合 ℃ 字符，在系统字体下渲染偏扁）；未来降雨伞色黑伞阈值从 50mm/h 下调至 32mm/h，与桌面当前天气图标口径一致，更易触发；清空游戏排行榜时同步清零该游戏的最高分纪录 |
| 1.5.0 | 2026-08-09 | 冻雨/冰雹专属天气效果：冻雨为冷白雨滴+冰晶，冰雹为密集白色冰粒并保留雷暴闪电，三个小游戏通用；雷暴/冰雹天气雨量收敛到中雨量级，突出闪电与冰雹主体，画面不再糊成一片 |
| 1.4.9 | 2026-08-09 | 小熊跳跳/摘星/迷宫背景与当前天气联动：晴天艳阳、阴天灰云，雨雪随天气降落；雨势分级：小雨雨点稀疏、大雨雨点密集，雷暴最密并带闪电；小熊奔跑动画改为一致的正面朝前视角，重绘精灵图；跑酷速度改为按距离平滑爬升，约 5000 分才达极速，节奏更从容；小熊农场作物生长放缓（最快 7.5 小时、最慢约 37 小时），枯萎条件放宽；小熊跳跳/摘星新增排行榜：记录前 20 名的分数、时间、地点与天气，前三名金/银/铜牌展示，支持一键清空纪录 |
| 1.4.8 | 2026-08-08 | 调试模式增强（体感温度自动跟随、未来 7 天温度覆盖、连续高温/寒潮预置场景）；跑酷视差山丘 Path 缓存优化 |
| 1.4.7 | 2026-08-08 | 修复天气图标显示回归；含帧循环降频、收藏流下沉、ABI 精简 |
| 1.4.5 | 2026-08-08 | 接入 CI 自动检查（静态检查/单测/代码扫描）；代码风格全量规范化；修复配置切换时雷达页可能不刷新的问题；发版自动化 |
| 1.4.4 | 2026-08-07 | 修复彩蛋口令丢失后的定位模式；积水预警阈值调整为 12 小时；修复通知空码误报；隐私政策同步更新至 1.4.4 |
| 1.4.3 | 2026-08-07 | 小熊农场作物改用自绘像素风（成熟带呼吸光效）；小熊迷宫选关可顺畅滚动；小时页折线图支持上下滑动页面；迷宫棋盘立体化、出口门开合动画 |

> 注：更早版本的更新内容已归档清理，需要旧版可查看 GitHub Releases 历史。

## 安装方法

1. 下载上表中的 APK 文件（手机浏览器打开本仓库即可直接下载，或点文件名查看后下载）
2. 打开文件，Android 会提示「为安装未知应用授权」，按提示允许（不同机型入口不同）
3. 若提示「手机管家拦截」，选择**继续安装**

## 功能一览

- 实况 + 18 小时预报 + 7 天日报
- 空气质量（欧标/美标 AQI、PM2.5、PM10、UV 等）
- 智能预警（强降雨、暴雪、寒潮、高温、积水、雷暴、冰雹等）
- 生活指数（穿衣、雨伞、洗车、晾晒、运动、感冒、舒适度）
- 季节贴士 + 农历
- 桌面图标随天气切换
- 桌面小组件（Glance）
- 通知提醒（仅在天气变化时提醒）

## 最低系统要求

- Android 8.0（API 26）及以上
