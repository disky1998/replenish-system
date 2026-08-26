# 智能补货辅助系统

现代化跨境电商智能补货与供应链决策系统。支持按日时序销量趋势分析、多周期加权销量重算、缺货断货补差、多仓成本智能路由、亏本风险预警与空海运比例智能分拆导出。

---

## 🚀 当前最新版本：v4.3.5 (2026-08-26)

### 📋 v4.3.5 更新日志 (Changelog)

1. **【极速体验】优化了趋势图的卡顿与闪烁问题**：
   - 升级为 120 FPS 极速轻量架构，表格 DOM 节点减少 98%，大幅提升千行数据滚动与翻页流畅度；
   - 引入 Hover Bridge 防抖通道，支持在表格单元格内直接左右滑动联动查看每日精准销量（无需移动至浮窗）。
2. **【时序解耦】优化了在线 Listing 下载的销量趋势图显示**：
   - 重构为 3 阶段独立时序算法（近 7 天在最左侧，8~14 天在中，15~30 天在右），顶端流线与微圆点自然呼应。
3. **【在线更新】全新上线自动版本检测机制**：
   - 刷新页面自动静默检测云端最新版；
   - 最新版时完全静默无打扰；有新版时全屏弹出升级详情并支持一键免跳转高速下载。
4. **【视觉焕新】升级系统品牌 Logo 与设置面板**：
   - 实装方案 H 极简纯矢量折线 Logo，现代 Apple/Linear 极简风；
   - 设置面板精简内置化，去除多余技术配置，清爽易用。
5. **【算法稳定】核心业务算法 100% 保持原样稳定**：
   - 加权日均重算、爆旺平警戒水位、建议补货量公式、空海结合守恒拆分与多仓成本路由等底层算法零变动。

---

## ⚡ 在线与下载链接

- 🏠 **GitHub 仓库**：[https://github.com/disky1998/replenish-system](https://github.com/disky1998/replenish-system)
- 🚀 **国内高速 CDN 直连下载**：[https://fastly.jsdelivr.net/gh/disky1998/replenish-system@main/补货辅助系统4.3.5.html](https://fastly.jsdelivr.net/gh/disky1998/replenish-system@main/%E8%A1%A5%E8%B4%A7%E8%BE%85%E5%8A%A9%E7%B3%BB%E7%BB%9F4.3.5.html)
- 🌐 **在线预览 (index.html)**：[https://fastly.jsdelivr.net/gh/disky1998/replenish-system@main/index.html](https://fastly.jsdelivr.net/gh/disky1998/replenish-system@main/index.html)
