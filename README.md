# Nalgnep 门户

[https://nalgnep.github.io/](https://nalgnep.github.io/) 是制造业算法学院的总入口。页面在本仓库根目录，GitHub Pages 从 `main` 分支的 `/` 发布。

桌面端左侧是菜单，窄屏收成抽屉，主区域用 iframe 打开同域页面。地址栏哈希可以直接分享到某一项，例如 [#spc](https://nalgnep.github.io/#spc)、[#bearing](https://nalgnep.github.io/#bearing)、[#roi](https://nalgnep.github.io/#roi)。顶栏「新标签打开」会离开门户，打开对应的原页面。

| 菜单 | 地址 |
| --- | --- |
| 工业 AI 算法课 | `/muse-projects/` |
| SPC 均值-极差图 | `/muse-projects/#spc` |
| 实战项目 | `/muse-projects/industrial-ai-projects/` |
| 轴承包络谱 | `/muse-projects/industrial-ai-projects/#p2-sim` |
| ROI 测算器 | `/muse-projects/industrial-ai-roi-calculator/` |
| 避坑指南 | `/muse-projects/industrial-ai-pitfalls/` |
| IoT 看板 | `/muse-projects/industrial-ai-iot-dashboard/` |
| 冰箱发泡演示 | `/foaming-demo/` |

样式和脚本都写在 `index.html` 里，不引用境外 CDN。`.nojekyll` 用来跳过 Jekyll。缺页时由 `404.html` 送回这些入口。课程和演示仍在 `muse-projects` 与 `foaming-demo` 两个仓库里，本仓库只做门户。
