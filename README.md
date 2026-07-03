# taken. — 汉化版 / Chinese Localization

> **"You opened this page. It already knows the following."**

这是 [Since You Arrived · Vol. IV: *taken.*](https://sinceyouarrived.world/taken) 的中文汉化版本。

原网页会在你打开的瞬间，如实展示你的浏览器交出了哪些信息——你的位置、设备、GPU、电池、字体、语言偏好……所有数据均来自**标准浏览器 API**，无需权限，无需登录。大多数网页都在做同样的事，但没有一个会告诉你。

---

## 关于原作

- **原作：** [Matt](https://bsky.app/profile/sinceyouarrived.world) / [Rise Up Labs](https://riseuplabs.app/)
- **原站：** [sinceyouarrived.world/taken](https://sinceyouarrived.world/taken)
- **系列：** *Since You Arrived*（共五卷）
- **版权：** 原作品版权归 Matt / Rise Up Labs 所有。汉化部分仅修改翻译内容，不改变原作的设计与功能。

### 系列各卷

- [Vol. I](https://sinceyouarrived.world/now) — 你在此期间的世界上发生的事
- [Vol. II](https://sinceyouarrived.world/sky) — 你错过的天空
- [Vol. III](https://sinceyouarrived.world/discovered) — 你脚下已有的东西
- **Vol. IV — taken.**（当前项目）
- [Vol. V](https://sinceyouarrived.world/distance) — 无人阅读之处

---

## 汉化说明

- 自动检测浏览器语言（`zh`），中文用户直接显示汉化界面
- 所有观察文案（位置、设备、GPU、电池、字体、偏好等）均已翻译
- 底部"来源与说明"面板完整汉化
- 页面标题、标签提示、实时计数器、分享弹窗均支持中文
- 保留原作的所有功能、设计、动画与隐私承诺——**不发送数据给第三方，不存储 Cookie，不保留 IP**

### 翻译修正

首次翻译中发现的几个遗漏已修复：
- 时段显示（如 `late in the evening`）补全为中文（晚间、上午、下午等）
- 设备类型（如 `a computer`）补全为中文描述（电脑、手机、平板）
- 标签页切换提示补全中文版本
- 页脚署名格式修正

---

## 许可

本仓库中的汉化修改部分采用 **MIT License**。  
原作品的权利归原作者所有，请尊重原始创作。

---

## 本地运行

```bash
# 直接用浏览器打开
open taken.html
```

或通过任意静态服务器托管：

```bash
python3 -m http.server 8080
# 访问 http://localhost:8080
```
