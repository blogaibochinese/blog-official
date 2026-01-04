## 计划步骤

### 1. 统一导航栏样式
- 将 `wise.html` 中导航栏相关的CSS样式（第28-96行）替换为 `index.html` 中的导航栏样式（第154-297行）
- 确保导航菜单的结构和链接与 `index.html` 一致

### 2. 统一汉堡菜单样式
- 确保 `wise.html` 中的汉堡菜单样式（第98-111行）与 `index.html` 中的样式（第299-312行）一致
- 检查汉堡菜单的JavaScript功能是否正常

### 3. 统一移动端底部按钮样式
- 将 `wise.html` 中移动端导航相关的CSS样式替换为 `index.html` 中的样式（第495-639行）
- 确保移动端导航的结构和链接与 `index.html` 一致

### 4. 统一右侧悬浮元素样式
- 将 `wise.html` 中右侧悬浮元素的CSS样式（第356-392行）替换为 `index.html` 中的样式（第14-142行）
- 确保悬浮元素的结构和JavaScript功能与 `index.html` 一致

### 5. 修复银行账户信息弹窗
- 添加银行账户信息模态框的HTML结构
- 添加 `showAccountModal()` 函数，用于显示银行账户信息模态框
- 在模态框中填充指定的银行信息：
  ```
  名称: HUANGLIN ZOU 
  账号: 44686943 
  银行代码: 60-83-82 
  账户类型: Bank 
  银行地址: BANKING CIRCLE S.A. 
  24 King William Street, EC4R 9AT London, United Kingdom
  ```
- 确保弹窗的关闭功能正常工作

## 预期结果
- wise.html页面的导航栏、汉堡菜单、移动端底部按钮、右侧悬浮元素与index.html保持一致
- 点击"查看银行账户信息"按钮时，能够正常弹出包含指定银行信息的模态框
- 弹窗可以正常关闭