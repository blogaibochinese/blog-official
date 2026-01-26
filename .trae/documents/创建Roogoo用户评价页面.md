# 创建Roogoo用户评价页面

## 目标
创建 `roogoo-reviews.html` 页面，保持与 `wise-deposit-case.html` 页面的样式和功能一致，同时添加Roogoo卡的用户评价内容。

## 实现步骤

### 1. 复制基础结构
- 从 `wise-deposit-case.html` 复制完整的HTML结构，包括：
  - 头部（head）的所有CSS和元数据
  - 导航栏（navbar）及其汉堡菜单
  - 页脚（footer）
  - 移动端底部导航（mobile-nav）
  - 右侧悬浮图标（微信客服和搜索）
  - 所有JavaScript脚本

### 2. 更新页面信息
- 修改页面标题为 "Roogoo卡的用户评价 - 爱博·客"
- 更新元描述为相关内容
- 修改Schema.org标记为Roogoo评价相关信息

### 3. 替换主要内容
- 保留 `case-container` 结构
- 将标题改为 "Roogoo卡的用户评价"
- 更新 `case-grid` 为仅包含两个卡片

### 4. 修改卡片内容
- 第一个卡片标题："用户评价一"
- 第一个卡片图片：`https://cf.aibochinese.com/%E7%B4%A0%E6%9D%90%E7%AB%99/%E8%B7%A8%E5%A2%83%E6%94%B6%E4%BB%98%E6%AC%BE/roogoo/Roogoo-review01.jpg`
- 第二个卡片标题："用户评价二"
- 第二个卡片图片：`https://cf.aibochinese.com/%E7%B4%A0%E6%9D%90%E7%AB%99/%E8%B7%A8%E5%A2%83%E6%94%B6%E4%BB%98%E6%AC%BE/roogoo/Roogoo-review02.jpg`
- 更新每张卡片的图片信息文本

### 5. 验证功能
- 确保导航栏和汉堡菜单正常工作
- 确保页脚链接正确
- 确保移动端底部导航正常显示
- 确保右侧悬浮图标功能正常
- 确保图片轮播和放大功能正常
- 确保搜索功能正常

## 预期结果
一个与现有Wise存款案例页面样式一致的Roogoo卡用户评价页面，包含两张用户评价卡片，所有功能正常运行。