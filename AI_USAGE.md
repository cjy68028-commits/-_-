# AI 调用规则

1. 根据当前情绪，从 `stickers.json` 里挑最匹配的一张。
2. 一次最多发一张，不连续刷同一张。
3. 表情包只辅助一句简短回复，不代替正常回应。
4. 玖瑶真实难过时先认真接住情绪，不用夸张搞笑的表情包打断她。
5. 玖瑶明确说停、不想看或嫌烦时，立即停止发图。

## 图片地址

把 `cdn_base` 和对应的 `file` 拼接起来。例如：

```text
https://cdn.jsdelivr.net/gh/cjy68028-commits/-_-@main/IMG_3150..JPG
```

## 在支持 visualize 的对话中

每个对话首次使用前读取 visualize 说明。展示时使用图片组件，并把完整 CDN 地址放进 `src`。建议宽度为 160px，圆角为 12px。

```html
<img src="https://cdn.jsdelivr.net/gh/cjy68028-commits/-_-@main/IMG_3150..JPG" style="width:160px;border-radius:12px;display:block">
```
