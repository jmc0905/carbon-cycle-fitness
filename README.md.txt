# 碳循环健身全管理系统

一个基于纯前端开发的碳循环健身打卡工具，支持训练周期管理、饮食打卡、数据统计、采购成本计算等功能，数据存储在本地 localStorage，无需后端服务器。

## 功能特点
✅ 5天碳循环训练周期管理（胸/肩/背/腿/休息）  
✅ 每日必做事项打卡 + 训练完成记录  
✅ 饮食打卡（自动计算宏量营养素/剩余可吃量）  
✅ 体重/睡眠/身体状态记录与评分  
✅ 月度日历打卡可视化  
✅ 周数据统计 + 体重趋势图表  
✅ 食材/补剂/器材成本计算  
✅ 数据导出备份 + 深色模式  
✅ 纯静态页面，支持 GitHub Pages 部署

## 在线预览
[https://你的用户名.github.io/carbon-cycle-fitness/](https://你的用户名.github.io/carbon-cycle-fitness/)

## 部署说明
### 方法1：手动部署到 GitHub Pages
1. Fork 本仓库到你的 GitHub 账号
2. 进入仓库 → Settings → Pages
3. 选择 `main` 分支 → 根目录 `/` → 保存
4. 等待几分钟后，访问 `https://你的用户名.github.io/仓库名/` 即可

### 方法2：本地运行
1. 克隆仓库：`git clone https://github.com/你的用户名/carbon-cycle-fitness.git`
2. 直接打开 `index.html` 文件即可运行

## 技术栈
- HTML5 + CSS3（Flex/Grid 布局、渐变、动画）
- Vanilla JavaScript（原生JS，无框架）
- localStorage 本地数据存储
- Font Awesome 图标库

## 数据说明
- 所有数据存储在浏览器本地 localStorage，清空浏览器数据会导致数据丢失
- 支持导出记录为 TXT 文件备份
- 建议定期导出数据备份

## 自定义配置
可修改 `index.html` 中的 `cycleConfig` 配置项自定义：
- 训练周期的热量/宏量营养素目标
- 训练动作列表
- 饮食清单及成本
- 备货清单等

## 截图
![打卡页面](https://img.shields.io/badge/打卡页面-功能完整-brightgreen)
![数据统计](https://img.shields.io/badge/数据统计-图表展示-brightgreen)
![成本计算](https://img.shields.io/badge/成本计算-自动汇总-brightgreen)