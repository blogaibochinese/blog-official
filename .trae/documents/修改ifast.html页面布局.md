# 修改ifast.html页面布局

## 第一步：将必要性和邀请优惠通道改为两栏布局

1. 在`main-content`中，将"必要性"和"邀请优惠通道"两个`content-section`包裹在一个新的容器`div`中，添加类名`two-column-container`
2. 为`two-column-container`添加CSS样式：
   - `display: flex`
   - `gap: 20px`
   - `margin-bottom: 40px`
3. 为每个`content-section`设置`flex: 1`，确保两栏宽度相等
4. 在移动端媒体查询中，为`two-column-container`添加`flex-direction: column`，使两栏在小屏幕上堆叠显示

## 第二步：调整支持国家的移动端展示

1. 修改`countries-grid`的移动端样式：
   - 将`grid-template-columns: 1fr`改为`grid-template-columns: repeat(3, 1fr)`，固定显示三列
   - 调整`gap`为`10px`，适应移动端屏幕
2. 修改`country-item`的移动端样式：
   - 保持`flex-direction: row`，确保国旗和文字水平排列
   - 减少`padding`为`10px`
   - 调整国旗大小为`width: 50px; height: 33px`
   - 减少国旗右侧`margin`为`10px`
3. 调整文字大小：
   - 将`country-name`字体大小改为`1rem`
   - 将`country-english`字体大小改为`0.8rem`

这样修改后，必要性和邀请优惠通道将在桌面端并列显示，在移动端堆叠显示；支持国家列表在所有屏幕尺寸下都将固定显示为三列。