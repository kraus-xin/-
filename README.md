# FatCatCal - 智能日历事件提取工具

## 功能概述

FatCatCal 是一个智能文本解析工具，能够帮助用户从文本中快速提取日历事件信息。它提供了直观的交互界面，让用户能够轻松地从文本中选择事件名称、时间和地点等关键信息。

### 核心功能

#### 1. 智能文本分割
- 自动识别并分割文本中的日期时间格式
- 支持简体和繁体中文日期时间格式：
  - 年份（如：2024年/2024年）
  - 月份（如：12月/12月）
  - 日期（如：15日、15号/15日、15號）
  - 时间（如：3点、15时、13:30/3點、15時、13:30）
  - 时间段（如：上午、下午、晚上、早上、中午/上午、下午、晚上、早上、中午）

#### 2. 交互式选择
- 支持三种选择类型：
  - 事件名称（绿色）
  - 时间（蓝色）
  - 地点（橙色）
- 多种选择方式：
  - 点击选择：单个字符的快速选择
  - 滑动选择：同一行内连续文本的快速选择
  - 支持垂直滚动浏览长文本

#### 3. 实时预览
- 实时显示已选择的内容
- 分类显示：
  - 事件名称
  - 时间信息
  - 地点信息

#### 4. 编辑功能
- 撤销功能：
  - 单击撤销：删除最后一个选择
  - 长按撤销：连续快速撤销多个选择
- 触觉反馈：操作时提供适当的触觉反馈，提升用户体验

### 使用说明

1. **文本选择**
   - 切换顶部选择类型（事件/时间/地点）
   - 点击或滑动选择相关文本
   - 不同类型的选择会以不同颜色标记

2. **预览区域**
   - 实时查看已选择的内容
   - 检查选择是否准确

3. **操作按钮**
   - 撤销：删除错误的选择
     - 短按：撤销单个选择
     - 长按：连续撤销多个选择
   - 完成：确认创建日历事件（需要同时包含事件名称、时间和地点）

### 技术特点

- 使用 SwiftUI 构建的现代化界面
- 支持手势识别和自然的交互方式
- 响应式设计，适配不同屏幕尺寸
- 优化的性能和流畅的动画效果
- 完善的错误处理和用户反馈机制

### 系统要求

- iOS 14.0 或更高版本
- 支持 iPhone 和 iPad

### 注意事项

- 选择时需要注意不同类型的文本不能重叠
- 完成按钮只有在三种类型的内容都选择后才能使用
- 建议按照事件名称、时间、地点的顺序进行选择，以获得最佳体验

## 开发者
- Kraus Sun